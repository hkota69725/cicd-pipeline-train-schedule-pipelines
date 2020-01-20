pipeline{
  agent any
  stages{
     stage('Buid'){
       steps{
         echo 'running build Auitomation'
         sh './gradlew build --no-daemon'
         archiveArtifacts artifacts: 'dist/trainSchedule.zip'
         }
        }
       }
      }

pipeline{
  agent any
  stages{
     stage('Buid'){
       steps{
         echo 'running build Automation'
         sh './gradlew build --no-daemon'
         archiveArtifacts artifacts: 'dist/trainSchedule.zip'
         }
        }
       }
      }

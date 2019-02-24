pipleline {
  agent any
  stages  {
     stage ('Build') {
       steps {
          echo 'Runing Build Automation'
          sh './gradlew build --no-daemon'
          archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
 }

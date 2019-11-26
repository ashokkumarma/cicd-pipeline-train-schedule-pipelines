pipeline {
  agent any
  stages {
    stage ('Build') {
     steps {
     echo 'running build automation'
     sg './gradlew build --no-daemon'
     archiveArtifacts artifatcs" 'dist/traiSchedule.zip'
     }
    }
  }
}

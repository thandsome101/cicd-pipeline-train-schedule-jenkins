pipeline {
 agent any 
  stages {
    stage ('Build') {
      steps {
        ech0 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainschedule.zip'
      }
    }
  }
}

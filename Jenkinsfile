@Library('sharedliberary') _

pipeline {
  agent any
  
  stages {
    stage('Install Nginx on Worker Node') {
      steps {
        script {
          mySharedLibrary.call('Worker1')
        }
      }
    }
  }
}

@Library('sharedliberary') _

pipeline {
  agent any
  
  stages {
    stage('Install Nginx on Worker Node') {
      steps {
        script {
          sharedliberary.call('Worker1')
        }
      }
    }
  }
}

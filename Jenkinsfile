@Library('sharedliberary') _

pipeline {
  agent any
  
  stages {
    stage('Install Nginx on Worker Node') {
           script {
          sharedliberary.call('Worker1')
      }
    }
  }
}

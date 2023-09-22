@Library('sharedliberary') _

pipeline {
  agent any
  
  stages {
    stage('Install Nginx on Worker Node') {
      steps {
        sharedliberary.call('Worker1')
      }
    }
  }
}

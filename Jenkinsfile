pipeline {
  agent any
  stages {
    stage('print') {
      steps {
        echo 'Output'
      }
    }
    stage('browser') {
      steps {
        cbt(credentialsId: 'd02f1fb2-8683-46fb-a90a-67b3b4105845', tunnelName: 'test', localTunnelPath: 'E:\\')
      }
    }
  }
}
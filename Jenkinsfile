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
        cbtSeleniumTest(operatingSystem: 'windows 7', browser: 'fiorefox 55', resolution: '800*600')
        cbt(credentialsId: 'd02f1fb2-8683-46fb-a90a-67b3b4105845', tunnelName: 'test', localTunnelPath: 'E:\\')
      }
    }
  }
}
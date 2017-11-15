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
      }
    }
  }
}
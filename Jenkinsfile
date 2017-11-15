pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'hello world'
      }
    }
    stage('browser') {
      steps {
        cbtSeleniumTest(operatingSystem: 'windows 8', browser: 'firefox 55', resolution: '800*600')
      }
    }
  }
}
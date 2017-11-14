pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        cbtSeleniumTest(operatingSystem: 'windows8', browser: 'firefox', resolution: '800*600')
      }
    }
  }
}
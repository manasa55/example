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
        cbt(credentialsId: 'd02f1fb2-8683-46fb-a90a-67b3b4105845', tunnelName: 'test', localTunnelPath: 'E:\\')
        cbtSeleniumTest(operatingSystem: 'windows 7 64-bit', browser: 'firefox 55', resolution: '800*600')
      }
    }
  }
}
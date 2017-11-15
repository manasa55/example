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
        cbt(credentialsId: 'ue99686fbf0f80db', tunnelName: 'test', localTunnelPath: 'E:\\')
      }
    }
  }
}
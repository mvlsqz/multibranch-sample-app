pipeline {
  agent {label 'agent'}
  options {
    buildDiscarder(logRotator(numToKeepStr: '5'))
  }
  stages {
    stage('Build') {
      steps {
        echo 'Hello world'
      }
    }
  }
}

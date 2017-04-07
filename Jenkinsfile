pipeline {
  agent any
  stages {
    stage('Unit Test') {
      steps {
        build 'mvn test'
      }
    }
    stage('Print message') {
      steps {
        echo 'Tests is done'
      }
    }
  }
}
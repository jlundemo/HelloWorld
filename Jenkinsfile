pipeline {
  agent any
  stages {
    stage('Unit Test') {
      steps {
        build(quietPeriod: -10, job: 'man test')
      }
    }
    stage('Print message') {
      steps {
        echo 'Tests is done'
      }
    }
  }
}
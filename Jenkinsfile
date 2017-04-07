pipeline {
  agent none
  stages {
    stage('start') {
      steps {
        echo 'Starts'
      }
    }
    stage('wait') {
      steps {
        sleep 10
      }
    }
    stage('build') {
      steps {
        build 'sh mvn compile'
      }
    }
  }
  environment {
    Test = 'test'
    QA = 'test'
  }
}
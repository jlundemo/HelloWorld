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
        build 'compile'
      }
    }
  }
  environment {
    Test = 'test'
    QA = 'test'
  }
}
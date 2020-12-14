pipeline {
  agent any
  stages {
    stage('test_stage') {
      steps {
        sh 'echo running build steps'
        echo 'running tests'
      }
    }

  }
  environment {
    test = 'test'
  }
}
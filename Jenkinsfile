pipeline {
  agent any
  stages {
    stage('Example') {
      environment {
        DEBUG_FLAGS = '-g'
      }
      steps {
        sh 'printenv'
      }
    }
  }
  environment {
    CC = 'clang'
  }
}
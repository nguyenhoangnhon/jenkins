pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        sh '''
          echo "PATH = ${PATH}"
          echo "M2_HOME = ${M2_HOME}"
         '''
      }
    }
    stage ('Build') {
       step {
         echo 'Hello World!'
       }
    }
  }
}

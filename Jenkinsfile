pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                sh 'cd /home/servertest'
                sh 'ls'
            }
        }
    }
}
            

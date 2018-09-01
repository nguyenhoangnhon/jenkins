pipeline {
    agent any
    environment {
        jobname = 'env.JOB_NAME'
    
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
                sh 'printenv'
            }
        }
    }
}
            

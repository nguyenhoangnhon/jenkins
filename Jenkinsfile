pipeline {
    agent any
    stages {
        stage('Example') {
            step { 
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}

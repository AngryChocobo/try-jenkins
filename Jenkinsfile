pipeline {
    agent any
    
    environment {
       SERVER_URL="set from Jenkinsfile"
    }

    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
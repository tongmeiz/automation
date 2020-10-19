pipeline {
    agent any

    stages {
        stage('Build Docker Image ') {
            steps {
                sh '''
                ls   -l
                docker --version
                // docker build -t "splunk" .
                // docker images
                '''
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
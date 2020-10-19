pipeline {
    agent any

    stages {
        stage('Build Docker Image ') {
            steps {
                sh '''
                ls  -al
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
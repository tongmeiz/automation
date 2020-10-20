pipeline {
    agent any

    stages {
        stage('Build Docker Image ') {
            steps {
                sh '''
                ls   -l
                podman --version
                docker --version
                // docker build -t "splunk" .
                podman images
                docker images
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

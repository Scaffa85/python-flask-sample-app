pipeline {
    agent {
        docker { image 'ubuntu:latest' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'apt update -f'
                sh 'apt upgrade -f'
            }
        }
    }
}

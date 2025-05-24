pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo 'Cloning the repository...'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
sh 'chmod +x scripts/deploy.sh && ./scripts/deploy.sh'
            }
        }
    }
}

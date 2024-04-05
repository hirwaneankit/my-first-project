pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Add build steps here
                sh 'echo "Building..."'
                sh 'echo "Hello this is my first Building Stage"'
            }
        }
        stage('Test') {
            steps {
                // Add test steps here
                sh 'echo "Testing..."'

                sh 'echo "Hello this is my First Testing Stage"'
            }
        }
        stage('Deploy') {
            steps {
                // Add deployment steps here
                sh 'echo "Deploying..."'
                sh 'echo "This is my first Deploying..."'
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/samrudhsivva/Python_Demo_Script', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Add any build steps if needed, like installing dependencies
            }
        }
        stage('Test') {
            steps {
                echo 'Running Tests...'
                // Run your test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Deployment steps, e.g., moving to a server, uploading, etc.
            }
        }
    }
}

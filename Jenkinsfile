// Jenkinsfile
pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code from SCM'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
                // sh 'mvn clean package' // Example build command
            }
        }
    }
}
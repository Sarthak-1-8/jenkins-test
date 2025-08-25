pipeline {
    // Run on any available machine.
    agent any

    stages {
        // Build stage: compile code, run static analysis, etc.
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }

        // Test stage: run unit tests, integration tests, etc.
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        // Deploy stage: push to a server, registry, etc.
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}

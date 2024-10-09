pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building project for production...'
                // Add build steps here, for example: compile code, generate artifacts, etc.
                sh 'echo "Compiling source code for main branch..."'
            }
        }
        stage('Test') {
            steps {
                echo 'Running production tests...'
                // Add test steps here, like unit tests or integration tests
                sh 'echo "Running production tests for main branch..."'
            }
        }
        stage('Deploy') {
            when {
                branch 'main'
            }
            steps {
                echo 'Deploying to production...'
                // Add deployment steps here, for example, SSH to server or call a cloud deployment
                sh 'echo "Deploying main branch to production environment..."'
            }
        }
    }
    
    post {
        always {
            echo 'Cleaning up after main pipeline...'
            // Clean-up steps (e.g., deleting temporary files)
        }
    }
}

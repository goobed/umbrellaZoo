pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building project for apple branch...'
                sh 'echo "Compiling source code for apple branch..."'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests for apple branch...'
                sh 'echo "Running tests for apple branch..."'
            }
        }
        // Deployment is skipped for the apple branch as it's not the main branch
    }
    
    post {
        always {
            echo 'Cleaning up after apple branch pipeline...'
            // Clean-up steps
        }
    }
}

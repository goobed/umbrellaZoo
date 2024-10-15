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
                sh 'echo "This is just another line!"'
            }
        }
    }
    post {
        always {
            echo 'Cleaning up after apple branch pipeline...'
            // Clean-up steps
        }
    }
}

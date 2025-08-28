pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building main branch: ${env.BRANCH_NAME}"
            }
        }
        stage('Test') {
            steps {
                echo "Running tests for main branch: ${env.BRANCH_NAME}"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying main branch: ${env.BRANCH_NAME}"
            }
        }
    }
}

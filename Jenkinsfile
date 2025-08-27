pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building new branch: ${env.BRANCH_NAME}"
            }
        }
        stage('Test') {
            steps {
                echo "Running tests for new branch: ${env.BRANCH_NAME}"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying new branch: ${env.BRANCH_NAME}"
            }
        }
    }
}

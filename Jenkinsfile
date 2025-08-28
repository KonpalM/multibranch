pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building head branch in repo: ${env.BRANCH_NAME}"
            }
        }
        stage('Test') {
            steps {
                echo "Running tests for head branch: ${env.BRANCH_NAME}"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying head branch: ${env.BRANCH_NAME}"
            }
        }
    }
}

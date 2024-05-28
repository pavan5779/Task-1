pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "Building the application"'
                // You can add build commands here (e.g., npm install, gulp build, etc.)
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests"'
                // You can add test commands here (e.g., npm test, pytest, etc.)
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying to test environment"'
                // You can add deployment commands here (e.g., scp, rsync, etc.)
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: "https://github.com/pavan5779/my-web-app.git", branch: 'main'
            }
        }

        stage('Build & Test') {
            steps {
                sh 'echo Building the application...'
                // Add your build and test commands here
            }
        }

        stage('Deploy to Test Environment') {
            steps {
                sh 'echo Deploying to the test environment...'
                // Add shell commands to deploy to your test server
            }
        }
    }

    triggers {
        pollSCM('* * * * *')
    }
}

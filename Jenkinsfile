pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/hanna667/jenkinspipeline.git'
            }
        }

        stage('Build') {
            steps {
                echo '🔧 Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying the application...'
            }
        }
    }
}

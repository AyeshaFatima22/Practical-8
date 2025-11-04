pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project... 🏗️'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests... ✅'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project... 🚀'
            }
        }
    }

    post {
        success {
            echo 'BUILD SUCCESS 🎉'
        }
        failure {
            echo 'BUILD FAILED 💔'
        }
    }
}

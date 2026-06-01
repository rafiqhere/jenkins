pipeline {
    // Basic Jenkins Pipeline testing aaaa
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'testing and Building...'
                // Add your build commands here
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deploy commands here
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished.'
        }
    }
}
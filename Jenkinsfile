pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                pwd
                ls
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}

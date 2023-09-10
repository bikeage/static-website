pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                ehco 'Building ${BUILD_ID}'

            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
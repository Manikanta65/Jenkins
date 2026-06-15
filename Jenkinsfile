pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh """

                rm -rf mani test yy

                """
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
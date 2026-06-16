pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh """
                      sudo docker run -d -p 80:80 manikanta65docker/frontend:1.0.0
                """
            }
        }
        stage('Test') {
            steps {
                sh """

                """
            }
        }
        stage('Deploy') {
            steps {
                sh """

                """
            }
        }
    }
}
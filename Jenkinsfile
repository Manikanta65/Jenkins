pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh """

                rm -rf mani test yy
                ls -l

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
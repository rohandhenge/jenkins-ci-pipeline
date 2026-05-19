pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Cloning Code'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Application'

                sh 'node app.js'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Application'
            }
        }

    }
}

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                nodejs('NodeJS'){
                    sh 'yarn install'
                }
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

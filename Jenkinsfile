pipeline {
    agent any

    stages {
        stage('Build') {
            agent { label 'master' }
            steps {
                echo 'Building..'
                echo 'sh vagrant up'
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
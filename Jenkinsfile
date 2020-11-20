pipeline {
    agent any

    stages {
        stage('Build') {
            agent { label 'master' }
            steps {
                echo 'Building..'
                echo 'Installing Packages'
                sh 'bash install.bash'
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
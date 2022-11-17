/* Requires the Docker Pipeline plugin */
/* pipeline {
    agent any
    stages {
        stage('Private repos..'){
            steps{
                echo 'Pipe sendo iniciada..'
            }
        }

        stage('build') {
            steps {
                bat 'docker ps'
            }
        }

        stage('finalizando..'){
            steps{
                echo 'Pipe sendo finalizada..'
            }
        }
    }
} */
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'node:16.17.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
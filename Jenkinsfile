/* Requires the Docker Pipeline plugin */
pipeline {
    /* agent any
    stages {
        stage('Iniciando..') {
            steps { 
                echo 'Iniciando pipeline'
            }
        }

        stage('second stage'){
            steps{
                echo 'Iniciando o segundo estagio'
            }
        }
    } */
    agent { docker { image 'node:16.17.1-alpine' } }
    stages {
        stage('Iniciando..'){
            echo 'Pipe sendo iniciada..'
        }

        stage('build') {
            steps {
                sh 'node --version'
            }
        }

        stage('finalizando..'){
            echo 'Pipe sendo finalizada..'
        }
    }
}
}
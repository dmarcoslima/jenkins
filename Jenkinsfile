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
    agent any
    stages {
        stage('Iniciando..'){
            steps{
                echo 'Pipe sendo iniciada..'
            }
        }

        stage('build') {
            steps {
                bat 'git --version'
            }
        }

        stage('finalizando..'){
            steps{
                echo 'Pipe sendo finalizada..'
            }
        }
    }
}
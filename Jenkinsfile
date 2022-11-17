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
    agent any /* { docker { image 'maven:3.8.6-openjdk-11-slim' } } */
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}
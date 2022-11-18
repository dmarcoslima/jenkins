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
    agent { docker { image 'portalparceiroclient:0.6' } }
    stages {
        stage('build') {
            steps {
                sh 'docker ps -a'
            }
        }
    }
}
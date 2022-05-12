pipeline {
    agent any
    stages {
        stage('Construir imagen') {
            steps {
                sh 'docker build -t hello-word:latest .'
            }
        }
        stage('subir imagen') {
            steps {
                sh 'echo subir imagen'
            }
        }
        stage('desplegar imagen') {
            /*
            agent {
                docker {
                    image 'gradle:6.7-jdk11'
                    reuseNode true
                }
            }
            */
            steps {
                sh 'echo desplegar imagen'
            }
        }
    }
}
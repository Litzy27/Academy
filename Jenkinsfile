pipeline {
    agent any
    stages {
        stage('download') {
            steps {
                sh '''
                ls
                echo "hola 1"
                '''
            }
        }
        stage('compilar') {
            steps {
                sh '''
                pwd
                echo "hola 2"
                '''
            }
            
        }
         stages {
        stage('testing') {
            steps {
                sh '''
                ls             
                echo "tareas de testing"
                '''
            }
        stage('deployar') {
            steps {
                sh '''
                echo "hola 3"
                '''
            }
        }
        
    }
}
    }

pipeline {
    agent any
    stages {
        stage('download') {
            steps {
                sh '''
                ls
                echo "hola"
                '''
            }
        }
        stage('compilar') {
            steps {
                sh '''
                pwd
                echo "hola mundo"
                '''
            }
        }
        stage('deployar') {
            steps {
                sh '''
                echo "hola mundo"
                '''
            }
        }
    }
}

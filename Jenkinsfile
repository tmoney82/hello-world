pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'python3 hello.py'
            }
        }
        stage('Test') {
            steps {
                sh '''
                which python
                which python3
                pwd
                ls
                '''
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
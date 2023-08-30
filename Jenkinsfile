pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh '''
                which python
                which python3
                pwd
                ls
                '''
            }
        }
        stage('Test') {
            steps {
                sh 'python3 hello.py'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
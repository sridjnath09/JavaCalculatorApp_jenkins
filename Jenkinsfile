pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                docker build -t sridjnath09/project .
                docker container run -dt -P sridjnath09/project 
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               sh "docker build -t sridjnath09/project ."
                echo "test"
              
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

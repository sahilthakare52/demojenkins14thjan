pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('new') {
            steps {
                echo 'new one'
            }
        }
        stage('failure') {
            steps {
                systemctl start docker
            }
        }
    }
}

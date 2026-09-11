pipeline {
    agent any

    stages {
        stage('Check Python') {
            steps {
                bat 'python --version'
            }
        }
        stage('Run Hello World') {
            steps {
                bat 'python helloWorldPankaj.py'
            }
        }
    }
}

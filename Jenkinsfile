pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
        stage('hello') {
            steps {
                
              sh 'python3 hello.py'
            }
        }
    }
}

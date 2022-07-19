pipeline {
    agent {
        docker { image 'tomcat:latest' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'ls'
            }
        }
        stage('build') {
            steps {
                sh 'pwd'
            }
        }
    }
}

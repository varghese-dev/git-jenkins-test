pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/varghese-dev/git-jenkins-test.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}

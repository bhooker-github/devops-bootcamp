pipeline {
    agent any
    tools {
     nodejs 'whateverwewant'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
                sh "npm install"
            }
        }
        stage('Build') {
            steps {
                sh "npm test"
            }
        }
    }
}

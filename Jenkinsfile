pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                nodejs('whateverwewant') {
                    sh "npm install"
                }
            }
        }
    }
}
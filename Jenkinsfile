pipeline {
    agent any
    tools {
     nodejs 'whateverwewant'
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh "npm install"
            }
        }
    }
}

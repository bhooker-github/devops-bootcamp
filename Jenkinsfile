pipeline {
    agent any
    tools {
     nodejs 'whateverwewant'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
        // stage('Code Quality') {
        //     steps {
        //         script {
        //            withSonarQubeEnv('sonar') {
        //                sh "${tool('sonar')}/bin/sonar-scanner"
        //            }
        //         }
        //     }
        // }
    }
}

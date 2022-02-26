pipeline {
    agent any
    tools { nodejs "node" }
    stages {
        stage('Start Build test1') {
            steps {
                sh "npm install"
            }
        }
        stage('Deploy') {
            steps {
                sh "npm start"
            }
        }
    }
}

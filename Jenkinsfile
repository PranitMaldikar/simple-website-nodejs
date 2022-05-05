pipeline {
    agent any
    tools { nodejs "node" }
    stages {
        stage('Build') {
            steps {
                echo "building npm website"
                sh "npm install nodemon --save-dev"
            }
        }
        stage('Deploy') {
            steps {
                echo "deploying website"
                sh "npm start"
            }
        }
    }
}

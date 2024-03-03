pipeline {
    agent any
    tools {"nodejs"}
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
        stage("test") {
            steps {
                sh './jenkins/scripts/test.sh
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'welcome to jenkins'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
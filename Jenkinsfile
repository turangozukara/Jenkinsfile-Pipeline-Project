pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Turan Gozukara'
                sh 'echo Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
            }
        }

        stage('test') {
            steps {
                echo 'Turan Gozukara'
                sh 'whoami'
                sh 'pwd'
                sh 'ls'
            }
        }
        stage('run') {
            steps {
                echo 'Turan Gozukara'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }

}
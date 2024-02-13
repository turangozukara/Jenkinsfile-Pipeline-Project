pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Turan Gozukara'
                sh 'echo Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
            }
        }
    }

    agent any
    stages {
        stage('test') {
            steps {
                echo 'Turan Gozukara'
                sh 'whoami'
                sh 'pwd'
                sh 'ls'
            }
        }
    }
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Turan Gozukara'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
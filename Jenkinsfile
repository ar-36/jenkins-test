pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'npm i'
                sh 'pwd'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Test Cases...'
                sh 'ls /home/ubuntu'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Changes...'
                sh './scripts/deploy.sh {URL}'
            }
        }
    }
}

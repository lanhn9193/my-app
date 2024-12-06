pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                script {
                    sh 'git status'
                    sh 'git config remote.origin.url https://github.com/lanhn9193/my-app.git'
                }
            }
        }
        stage('Clone Repo Github'){
            steps{
                echo 'Clone Repo Github'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}

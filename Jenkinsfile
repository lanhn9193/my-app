pipeline {
    agent any
    stages {
        stage('Checkout'){
            steps{
                // Kiểm tra thư mục hiện tại
                sh 'pwd'
                sh 'ls -la'

                // Lệnh Git checkout (nếu sử dụng Git SCM)
                checkout scm
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

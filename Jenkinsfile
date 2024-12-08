pipeline {
    agent any
    stages {
        stage('Checkout Develop'){
            steps{
                // Kiểm tra thư mục hiện tại
                sh 'pwd'
                sh 'ls -la'

                // Lệnh Git checkout (nếu sử dụng Git SCM)
                checkout scm
            }
        }
        stage('Clone Repo Github Develop'){
            steps{
                echo 'Clone Repo Github Develop'
            }
        }
        stage('Build Develop') {
            steps {
                echo 'Building Develop...'
            }
        }
        stage('Test Develop') {
            steps {
                echo 'Testing Develop...'
            }
        }
        stage('Deploy Develop') {
            steps {
                echo 'Deploying Develop...'
            }
        }
    }
}

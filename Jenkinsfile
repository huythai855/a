pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Đảm bảo Jenkins checkout mã nguồn từ repository GitHub
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Thực hiện các bước build ứng dụng của bạn ở đây
                sh echo 'Building...'
            }
        }
        stage('Run Terminal Tasks') {
            steps {
                // Thực hiện các tác vụ trên terminal
                sh echo "Running terminal task..."
            }
        }
    }
}
pipeline {
    agent any
    stages {
        stage('Clone repository') {
            steps {
                // Checkout code from GitHub
                git 'https://github.com/MariaGeorge22/CI-CD.git'
            }
        }
        stage("Run App") {
            steps {
                bat "python app.py"
            }
        }
    }
}

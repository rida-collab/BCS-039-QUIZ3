pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Pull code from version control (if any)
                checkout scm
            }
        }
        stage('Run Python Script') {
            steps {
                bat '"D:\\Anaconda\\python.exe" hello.py'
               
            }
        }
    }
}

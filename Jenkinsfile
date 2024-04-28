pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Add build steps here
                bat 'echo Building...'
            }
        }
        stage('Test') {
            steps {
                // Add test steps here
                bat 'echo Testing...'
            }
        }
        stage('Deploy') {
            steps {
                // Add deployment steps here
                // Copy HTML files to XAMPP htdocs directory
                bat 'xcopy /s /y "C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\HTML DEPLOYMENT DECLARATIVE PIPELINE" "C:\\xampp\\htdocs"'
            }
        }
        stage('Monitor') {
            steps {
                // Add monitoring steps here
                bat 'echo Monitoring...'
            }
        }
    }
}

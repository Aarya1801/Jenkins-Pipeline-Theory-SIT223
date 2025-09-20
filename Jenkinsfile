pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build code using Maven'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Run unit and integration tests using JUnit'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Analyze code using SonarQube'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Run security scan using OWASP ZAP'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploy to staging server (AWS EC2)'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Run integration tests on staging environment'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploy to production server (AWS EC2)'
            }
        }
    }
}

pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Build: Compile and package the application using Maven.'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Unit and Integration Tests: Run automated unit and integration tests using JUnit and Selenium.'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Code Analysis: Analyse source code quality using SonarQube.'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Security Scan: Scan the application for known vulnerabilities using OWASP Dependency-Check.'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy to Staging: Deploy the application to an AWS EC2 staging server.'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Integration Tests on Staging: Run automated API integration tests using Postman/Newman.'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy to Production: Deploy the application to an AWS EC2 production server.'
            }
        }
    }
}

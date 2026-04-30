pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build: Using Maven to compile and package the code.'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Testing: Using JUnit and Selenium.'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Code Analysis: Using SonarQube.'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Security Scan: Using OWASP Dependency-Check.'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to staging server using AWS EC2.'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running staging integration tests using Postman/Newman.'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying to production server using AWS EC2.'
            }
        }
    }
}

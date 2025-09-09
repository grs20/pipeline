pipeline {
    agent any
    stages {
        stage('Build') { steps { echo 'Build with Maven' } }
        stage('Unit and Integration Tests') { steps { echo 'Run tests' } }
        stage('Code Analysis') { steps { echo 'Analyze code with SonarQube' } }
        stage('Security Scan') { steps { echo 'Security scan with Snyk' } }
        stage('Deploy to Staging') { steps { echo 'Deploy to staging server' } }
        stage('Integration Tests on Staging') { steps { echo 'Run integration tests on staging' } }
        stage('Deploy to Production') { steps { echo 'Deploy to production server' } }
    }
}

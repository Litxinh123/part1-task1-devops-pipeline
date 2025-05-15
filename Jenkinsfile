pipeline {
  agent any
  triggers {
    pollSCM('* * * * *')
  }
  stages {
    stage('Build') {
      steps { echo 'Building the application...' }
    }
    stage('Unit & Integration Tests') {
      steps { echo 'Running tests...' }
    }
    stage('Code Analysis') {
      steps { echo 'Analyzing code quality...' }
    }
    stage('Security Scan') {
      steps { echo 'Scanning for vulnerabilities...' }
    }
    stage('Deploy to Staging') {
      steps { echo 'Deploying to staging...' }
    }
    stage('Integration Tests on Staging') {
      steps { echo 'Testing in staging environment...' }
    }
    stage('Deploy to Production') {
      steps { echo 'Deploying to production...' }
    }
  }
}

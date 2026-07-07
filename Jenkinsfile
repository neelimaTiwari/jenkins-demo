pipeline {
    agent any
    stages {
        stage('Checkout Info') {
            steps {
                bat 'echo Jenkins pulled this pipeline straight from my GitHub repo'
                bat 'echo testing auto build 1'
                bat 'dir'
            }
        }
        stage('Build') {
            steps {
                bat 'echo Building...'
            }
        }
        stage('Test') {
            steps {
                bat 'echo Testing...'
            }
        }
    }
}
pipeline {
    agent any
    stages {
        stage('Install') {
            steps {
                sh 'yarn'
            }
        }
        stage('Buil') {
            steps {
                sh 'yarn build'
            }
        }
        stage('Test') {
            steps {
                sh 'yarn test'
            }
        }
    }
}
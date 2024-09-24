pipeline {
    agent any
    stages {
        stage('git Checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/nanabenn122/aws-cicd.git'
            }
        }
        stage('test'){
            steps{
                sh 'echo test'
            }
        }
    }
}
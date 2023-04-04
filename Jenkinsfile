pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build app'
            }
        }
        stage('Test') {
            steps {
                echo 'Test app'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy App'
            }
        }
        
        
    }
    post{
        always{
            emailext body: '', subject: 'pipeline status', to: 'praveen.devops95@gmail.com'
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
            }
        }
        stage('Deploy') {
            when {
                branch main
            }
            steps {
                echo 'Deploying'
            }
        }
    }
}

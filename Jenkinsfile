pipeline {
    agent any 
    stages {
        stage('Prepare') {
            steps {
                echo 'Installing Node.js 22...'
            }
        }
        stage('Build') {
            steps {
                sh 'npm --version'
            }
        }
        stage('Test') {
            steps {
                echo "JENKINS_URL is: ${env.JENKINS_URL}"
            }
        }
    }
}

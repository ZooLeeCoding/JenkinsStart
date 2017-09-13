pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -'
                sh 'apt-get install -y nodejs'
                sh 'npm --version'
            }
        }
    }
}
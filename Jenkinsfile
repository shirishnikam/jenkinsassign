pipeline {
    agent any

    stages {
        stage('Copy Files') {
            steps {
                sh 'mkdir -p /opt/gitcontent'
                sh 'cp -r * /opt/gitcontent/'
            }
        }
    }
}












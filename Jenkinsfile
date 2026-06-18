pipeline {
    agent any

    stages {
        stage('Pull Git Content') {
            steps {
                sh 'mkdir -p /opt/gitcontent'
                sh 'cp -r * /opt/gitcontent/'
            }
        }
    }
}

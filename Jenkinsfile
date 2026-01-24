pipeline {
    agent any
    stages {
        stage('Test Connection') {
            steps {
                sh 'echo "Files from GitHub:"'
                sh 'ls'
                sh 'cat index.html'
            }
        }
    }
}

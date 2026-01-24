pipeline {
    agent any
    stages {
        stage('Test Connection') {
            steps {
                sh 'echo "Files from GitHub:"'
                sh 'ls'
                sh '''
                echo "Starting local server..."
                python3 -m http.server 9000 &
                sleep 3
                '''
            }
        }
    }
}

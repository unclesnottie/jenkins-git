pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Whazzup People"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}

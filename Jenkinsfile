pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World111"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}

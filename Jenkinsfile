pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World Dan"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}

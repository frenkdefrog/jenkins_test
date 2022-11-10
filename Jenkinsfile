pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shells teps works too"
                    ls -lah
                '''  
            }
        }
    }
}
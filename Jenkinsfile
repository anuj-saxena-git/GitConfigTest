pipeline {
    agent any
    stages {
        stage (' setting variable') {
            steps {
                sh '''
                    git config --global http.postBuffer 1048576001
                '''
            }
        }
    }
}

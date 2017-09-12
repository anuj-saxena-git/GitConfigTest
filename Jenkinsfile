pipeline {
    agent any
    stages {
        stage ('checkout_scm') {
            checkout
        }
        stage (' setting variable') {
            steps {
                sh '''
                    git config --global http.postBuffer 1048576
                '''
            }
        }
    }
}

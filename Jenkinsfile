pipeline {
    agent any
    stages {
        stage (' setting variable') {
            steps {
                sh '''
                    #git config --global http.postBuffer 1048576
                    git config --global pack.windowMemory "32m"
                '''
            }
        }
    }
}

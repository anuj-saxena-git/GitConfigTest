pipeline {
    agent any
    stages {
        stage (' setting variable') {
            steps {
                sh '''
                    #git config --global http.postBuffer 1048576
                    #git config --global pack.windowMemory "32m"
                    git config --global http.postBuffer 1048576
                    git config --global core.packedGitLimit 128m
                    git config --global core.packedGitWindowSize 128m
                    git config --global pack.deltaCacheSize 128m
                    git config --global pack.packSizeLimit 128m
                    git config --global pack.windowMemory 128m
                '''
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('scm checkout') {
            steps {
                // Get some code from a GitHub repository
                git url: 'https://github.com/sai2712/devops.git', branch: 'main
            }
        }
    }
}

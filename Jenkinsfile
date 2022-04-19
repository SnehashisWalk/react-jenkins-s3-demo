pipeline {
    agent { label "linux"} 

    stages {
        stage('Hello') {
            steps {
                sh '''
                    aws --version
                '''
            }
        }
    }
}
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh "docker image ls"
            }

            post {
                success {
                  sh "echo yay"
                }
            }
        }
    }
}

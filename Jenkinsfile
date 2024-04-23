Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'node:20.11.1' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}

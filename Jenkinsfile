pipeline {
    agent { docker 'maven:3.8.4' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}

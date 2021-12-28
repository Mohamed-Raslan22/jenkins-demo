pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-8-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
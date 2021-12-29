pipeline {
        agent { docker { image 'maven:3.3.3' } }
        stages {
            stage('build') {
                environment {
                  HOME="."
                }
                steps {
                    sh 'mvn --version'
					sh 'mvn clean install'
					sh 'mvn clean compile'
                }
           }
        }
    }
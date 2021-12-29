pipeline {
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
pipeline {
    tools {
        jdk 'openjdk-1.8'
        maven 'Maven_3_5_2'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh "mvn clean install"
            } 
        }
    }
}
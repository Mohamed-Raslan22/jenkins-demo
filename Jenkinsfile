	pipeline { 
	agent any  
	stages { 
		stage('Build') { 
			steps { 
			   echo 'This is a minimal pipeline.' 
			   sh 'mvn --version' 
			   sh 'mvn clean install'
			  
			}
		}
	}
	}
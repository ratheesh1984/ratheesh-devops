pipeline {
    // agent any 
    agent { docker { image 'maven3.6.3'} }
    stages {
	stage('Build') {
	     steps {
                 sh "mvn --version"
                 echo "Build"
		}
	}
	stage('Test') {
	    steps {
                echo "Test"
		}
	}
	stage('Integration') {
	    steps {
                echo "Integration"
	        }
	   }
	}
}

pipeline {
/*
	environment {
        MAVEN_HOME = tool('maven3.6.0')
    }
*/
	agent 'none'


	stages {
	    stage('Checkout') {
	        steps {
				checkout scm			        }
		    }
		stage('Build') {
	        steps {
//				sh '${MAVEN_HOME}/bin/mvn install'
				sh '/home/praveen/Distros/apache-maven-3.6.0/bin/mvn install'
	        }
		}
	}
}

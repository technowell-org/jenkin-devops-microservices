pipeline {
	agent:any {docker {image 'maven:any'}}
	stages {
	stage('Build') { 
		steps {	
		sh 'mvn --version'
		echo "Build"
		}
	}
	stage('Test') {
		steps {	
		echo "Test"
		}
	}
	stage('Integration Test') {
		steps {	
		echo "Integration Test"
		}
	}
	}
	
}

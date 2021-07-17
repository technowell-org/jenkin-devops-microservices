pipeline {
	agent {docker {image 'maven:3.6.3'}}
	stage('Build') {
		sh 'mvn --version'
		echo "Build"
	}
	stage('Test') {
		echo "Test"
	}
	stage('Integration Test') {
		echo " IntegrationTest"
	}
	
}

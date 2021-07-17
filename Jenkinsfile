pipeline {
	agent any
    //agent { docker { image 'maven:3.3.3' } }
	environment {
		dockerHome = tool 'myDocker'
		mavenHome = tool 'myMaven'
		PATH = "$dockerHome/bin:$mavenHome/bin:$PATH"
	}

    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
				sh 'docker version'
            }
        }
    }
}
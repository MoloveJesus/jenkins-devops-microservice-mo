pipeline {
	//agent any
	agent { docker { image 'maven:3.6.3'}}
	stage('Build') {
		steps {
			sh 'mv --version'
			echo "Build"
		}
	}
	stage('Test') {
		steps {
			echo "Build"
		}
	}

	stage('Integration Test') {
		steps {
			echo "Build"
		}
	}
}
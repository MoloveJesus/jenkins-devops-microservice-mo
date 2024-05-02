pipeline {
	//agent any
	agent { docker { image 'maven:3.9.6'}}
	stages {
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
}

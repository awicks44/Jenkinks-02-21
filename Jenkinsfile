pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo 'Hello World! - Building'
			}
		}

		stage('Test') {
			steps {
				echo 'Hello World! - Testing'
			}
		}
	}

	post {
		success {
			echo 'Successful Build'
		}
	}
}
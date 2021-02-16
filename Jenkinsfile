pipeline {
	agent any
	stages {
		stage('Stage 1') {
			steps {
				echo 'Hello World!'
			}
		}
	}
	
	post {
		success {
			echo 'Successful Build'
		}
	}
}

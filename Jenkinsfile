pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
				echo "Test"
				echo "Integration Test"
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
	
	post {
		always {
			echo 'Im awesome. I run always'
		}
		success {
			echo 'Im run when you are successful'
		}
		failure {
			echo 'Im run when you fail'
		}
	}
}

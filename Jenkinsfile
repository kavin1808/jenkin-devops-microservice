//node {
//		echo "Build"
//		echo "Test"
//		echo "Integration Test"
//}
// Declarative
pipeline {
	agent any
	stages {
		stage('Build') { 
			steps {
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
	
	pose {
		always {
			echo "I am awesome. I run always"
		}
		success {
			echo "I run when you are successful"
		}
		failure {
			echo "I run only when you fail"
		}
	}
}

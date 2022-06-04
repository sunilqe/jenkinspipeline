pipeline {

agent any

stages {

	stage('SCM') {
		steps {
			echo "Pull code from git"
		}
	}

	stage('Deploy') {
		steps {
			echo "Deploy the code"
		}

	}

	stage('Test') {
		steps {
			echo "Test the webapp"
		}
	}

}

}
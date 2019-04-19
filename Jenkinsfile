pipeline {

	agent any

	stages {
		stage('Build') {
			steps {
				sh "echo hi"
				echo env.VAR2
				sh "printenv"
			}
		}
	}

}

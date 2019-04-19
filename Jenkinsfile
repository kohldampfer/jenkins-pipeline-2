pipeline {

	agent any

	stages {
		stage('Build') {
			steps {
				sh "echo hi"
				sh "echo ${VAR2}"
				echo env.VAR2
				sh "printenv"
			}
		}
	}

}

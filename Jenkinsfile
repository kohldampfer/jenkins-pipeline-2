pipeline {

	agent any

	properties ([
		parameters([
			string(name: 'VAR2', defaultValue: 'TESTING', description: '',)
		])
	])

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

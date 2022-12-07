pipeline{
	agent any
	stages {
		stage('lister les variables'){
			steps {
				sh 'printenv'
			}
		}
		stage('utilisation des variables'){
			steps {
				echo 'Hello World!'
			}
		}
	}
}
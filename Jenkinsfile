pipeline{
	agent any
	environment {
		USER_NAME = 'LE GUELLANFF'
		PREFERED_COLOR = 'BLUE'
	}	
	stages {
		stage('lister les variables'){
			steps {
				sh 'printenv'
			}
		}
		stage('utilisation des variables'){
			steps {
				echo env.USER_NAME
				echo env.PREFERED_COLOR
			}
		}
	}
}
pipeline {
	agent any
		stages {
		stage('build') {
			steps {
				echo 'I am executing stage build'
			}
		}
		stage('test') {
			steps {
				echo 'In pipeline, We take decision. Can we proceed?'
			}
		}
		stage('deploy') {
			steps {
				echo "Running Stage Test"
			}
		}
		stage('sonarqube') {       
			steps {
			echo "Running another test job sonarqube"
			}        
		}
	}
}

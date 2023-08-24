pipeline {
	agent any
	
	stages {
		stage ('compile') {
			steps {
				sh 'mvn clean compile'
				
				}
			}
		stage ('test') {
			steps {
				sh 'mvn test'
				}
				}
		stage ('install') {
			steps {
				sh 'mvn install'
				}
			}
			
		stage ('branch') {
			steps {
				echo "this master"
				}
				}
			}
		}

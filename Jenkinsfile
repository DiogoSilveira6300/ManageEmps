pipeline {
	agent anytools {
		jdk 'jdk8'
		maven 'maven'
	}stages {
		stage('test java installation') {
		steps {
			sh 'java -version'
			}
		}stage('test maveninstallation') {
			steps {
				sh 'mvn -version'
				}
			}
		}
	}

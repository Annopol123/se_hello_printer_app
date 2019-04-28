pipeline {
    agent any
    stages {
        stage('Deps') {
            steps {
	                  sh 'make deps'
        	}
        }
        stage('Test') {
            stape {
                    sh 'make test'
               }
        }
    }
}

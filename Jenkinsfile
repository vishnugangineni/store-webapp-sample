pipeline {
    agent none 
    stages {
        stage('Maven build') {
            agent {
				label 'maven'
			}
            steps {
                sh 'mvn clean package'
            }
        }
        
    }
}
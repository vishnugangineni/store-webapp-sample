pipeline {
    agent none 
    stages {
        stage('Maven build') {
            agent {
				label 'slave1'
			}
            steps {
                sh 'mvn clean package'
            }
        }
        
    }
}
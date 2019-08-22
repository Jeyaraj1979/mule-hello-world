pipeline {
    agent any 
    stages {
        stage('Clone and Clean') { 
            steps {
    			bat "mvn clean"
            }
        }
        stage('Build') { 
            steps {
                bat "mvn install" 
            }
        }
        stage('Package') { 
            steps {
                bat "mvn package"
            }
        }
    }
}
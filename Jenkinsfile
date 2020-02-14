pipeline {
    agent any 
    stages {
        stage( '--clean it') { 
            steps {
                sh "mvn clean"
            }
        }
        stage('Test') { 
            steps {
                sh "mvn test " 
            }
        }
        stage('package') { 
            steps {
                sh "mvn package" 
            }
        }
    }
}

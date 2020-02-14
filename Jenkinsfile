pipeline {
    agent any 
    stages {
        stage( '--clean it') { 
            steps {
                sh "/opt/apache-maven/bin/mvn clean"
            }
        }
        stage('Test') { 
            steps {
                sh "/opt/apache-maven/bin/mvn test " 
            }
        }
        stage('package') { 
            steps {
                sh "/opt/apache-maven/bin/mvn package" 
            }
        }
    }
}

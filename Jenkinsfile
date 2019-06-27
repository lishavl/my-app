

pipeline {
    agent any 
    environment {
              JAVA_HOME = "/usr/lib/jvm/java-8-openjdk-amd64/jre"
        }
    stages {
        stage('---clean---') { 
            steps {
                sh "mvn clean"
            }
        }
        stage('---test---') { 
            steps {
               sh "mvn test"
            }
        }
        stage('---package---') { 
            steps {
                sh "mvn package"
            }
        }
    }
}



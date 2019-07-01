

pipeline {
    agent any 
    environment {
              JAVA_HOME = "/usr/"
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



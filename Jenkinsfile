pipeline {
    agent any
    stages {
        stage ("Build Backend") {
            steps {
                bat "mvn package -DskipTests=true"
            }
        }
        stage ("Unit Tests") {
            steps {
                bat "mvn test"
            }
        }        
        stage ("Sonar Analysis") {
            environment {
                scannerHome = tool "SONAR_SCANNER"
            }
            
        }
    }
} 

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
    }

} 
pipeline {
    agent any
    stages {
        stage ("Build Backend") {
            steps {
                bat "mvn package -DskipTests=true"
            }
        }
    }
} 
pipeline {
    agent any
    stages {
        stage ("Build Backend") {
            steps {
                bat "mvn packag -DskipTests=true"
            }
        }
    }
} 
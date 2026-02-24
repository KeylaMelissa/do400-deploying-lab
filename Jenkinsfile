pipeline {
    agent {
        node { label "maven" }
    }

    stages {
        stage("Test") {
            steps {
                sh 'chmod +x mvnw'
                sh "./mvnw verify"
            }
        }
    }
}
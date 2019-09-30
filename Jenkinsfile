pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo hai vinay
                archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true 
            }
        }
    }
}

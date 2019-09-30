pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo hai vinay' 
                archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true 
            }
        }
    }
}

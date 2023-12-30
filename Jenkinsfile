pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                withDockerRegistry(credentialsId: 'dockerhub1_id', url: 'https://index.docker.io/v1/') {
                    sh 'docker build -t 211273822112761421127474/dockerpipelines:test-v01'
                }
            }
        }
      
    }
}

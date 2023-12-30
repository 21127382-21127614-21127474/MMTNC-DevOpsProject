pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                withDockerRegistry(credentialsId: 'dockerhub1_id', url: 'https://index.docker.io/v1/') {
                    docker build -t 21127614/TestPipeline
                }
            }
        }
      
    }
}

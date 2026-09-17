@Library('my-shared-library') _
pipeline{
    agent any
    stages{
        stage('test-shared-library'){
            steps{
                dockerPipeline('avejlanjekar45/jenkins-docker-pipeline')
            }
        }
    }
}

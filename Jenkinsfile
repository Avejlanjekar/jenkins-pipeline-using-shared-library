@Library('my-shared-library') _
pipeline{
    agent any
    stages{
        stage('Check Workspace') {
            steps {
                sh 'pwd'
                sh 'ls -la'
            }
        }
        stage('test-shared-library'){
            steps{
                dockerPipeline('avejlanjekar45/jenkins-docker-pipeline-using-sl','dockerhub-credentials','https://registry.hub.docker.com')
            }
        }
    }
}

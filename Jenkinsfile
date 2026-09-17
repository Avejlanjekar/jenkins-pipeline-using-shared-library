@Library('my-shared-library') _
pipeline{
    agent any
    stage('Check Workspace') {
            steps {
                sh 'pwd'
                sh 'ls -la'
            }
    }
    stages{
        stage('test-shared-library'){
            steps{
                dockerPipeline('avejlanjekar45/jenkins-docker-pipeline-using-sl')
            }
        }
    }
}

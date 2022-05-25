pipeline {

    agent any
    //agent { dokcer {image 'maven:3.6.3'} }
    stages{
        stage('Build') {
            steps {
                echo "Build"
                echo "PATH - $PATH"
                echo "Build_NUMBER - $env.Build_NUMBER"
                echo "Build_ID - $env.Build_ID"
                echo "JOB_NAME -$env.JOB_NAME"
                echo "Build_TAG -$env.Build_TAG"
                echo "BUILD_URL -$env.BUILD_URL"
            }
        }
        stage('Test') {
            steps {
                echo "Test"
            }
        }
        stage('IntegrationTest') {
            steps {
                echo "IntegrationTest"
            }
        }
    }
}


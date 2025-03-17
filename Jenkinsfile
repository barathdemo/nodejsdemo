pipeline {
    agent any 
    stages {
        stage('Docker Build') { 
            steps {
                echo "This is Build stage."
                echo "docker build -t barath2707/docker:$BUILD_NUMBER for testing"
                echo "Printing Job URL : $JOB_URL"
            }
        }
        stage('Docker push') { 
            steps {
                echo "This is docker push stage."
                echo "docker push barath2707/docker:$BUILD_NUMBER for qa"
            }
        }
    }
}

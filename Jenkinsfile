pipeline {
    agent any
    environment {
        JENKINS_URL = "${env.JENKINS_URL}"
        BUILD_ID = "${env.BUILD_ID}"
    }
    stages {
        stage('Display Info') {
            steps {
                echo "Jenkins URL: ${env.JENKINS_URL}"
                echo "Build ID: ${env.BUILD_ID}"
            }
        }
    }
}

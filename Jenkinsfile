pipeline {
    agent any
    environment {
        JENKINS_URL = "${env.JENKINS_URL}"
        BUILD_ID = "${env.BUILD_ID}"
    }
    stages {
        stage('Display Environment Variables') {
            steps {
                script {
                    echo "JENKINS_URL: ${JENKINS_URL}"
                    echo "BUILD_ID: ${BUILD_ID}"
                }
            }
        }
    }
}

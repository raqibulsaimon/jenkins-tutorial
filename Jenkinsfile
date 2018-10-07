pipeline {
    agent any

    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE    = 'sqlite'
    }
    stages {
        stage('Build') {
            steps {
                echo "${DB_ENGINE}"
                echo "${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}

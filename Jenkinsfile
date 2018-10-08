pipeline {
    agent any
    stages {
        stage('Deploy') {
            when {
              expression {
                currentBuild.result == null || currentBuild.result == 'SUCCESS' 
              }
            }
            steps {
                sh 'echo "publishing"'
                echo "current build: ${currentBuild.result}"
                def username = 'Jenkins'
                echo 'Hello Mr. ${username}'
                echo "I said, Hello Mr. ${username}"
            }
        }
    }
}

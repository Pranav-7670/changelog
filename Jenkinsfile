pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "testing how change log workslsdvksvknnn...................."
            }
        }
    }

    post {
        always {
            script {
                def changelog = ''
                if (currentBuild.result == 'SUCCESS') {
                    changelog = sh(script: 'git log --pretty=format:"%h - %an, %ar : %s"', returnStdout: true).trim()
                }
                echo "Changelog since last successful build:\n${changelog}"
            }
        }
    }
}

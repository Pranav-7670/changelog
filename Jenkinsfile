pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "testing chnage log how it works"
            }
        }
    }

    post {
        always {
            // Generate changelog report
            changelog
        }
    }
}

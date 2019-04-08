pipeline {
    agent any
    stages {
        stage ('test') {
            steps {
                echo 'His next'
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}

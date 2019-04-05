pipeline {
    agent any
    stages {
        stage ('test') {
            steps {
                echo 'His'
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}

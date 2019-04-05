pipeline {
    agent any
    stages {
        stage ('test') {
            steps {
                echo 'Hi'
                echo 'Hi'
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}

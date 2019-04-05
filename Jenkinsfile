pipeline {
    agent any
    stages {
        stage ('test') {
            steps {
                echo 'Hi'
                sh 'ls'
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}

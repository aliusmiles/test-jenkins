pipeline {
    agent any
    stages {
        stage ('test') {
            steps {
                echo 'Hi'
                sh 'ls'
                echo 'a'
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}

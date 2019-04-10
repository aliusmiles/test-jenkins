pipeline {
    agent any
    stages {
        stage ('test') {
            steps {
                echo 'Hi!!'
                echo 'no'
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}

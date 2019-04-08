pipeline {
    agent any
    stages {
        stage ('test') {
            steps {
                echo 'Hi!!'
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}

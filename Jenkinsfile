pipeline {
    agent any
        stage ('test') {
            steps {
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

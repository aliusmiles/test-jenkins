pipeline {
    agent any
    stages {
        stage ('test') {
            when {
                not {
                    changelog '\\[skip-ci|ci-skip\\]'
                }
            }
            steps {
                echo 'Hi!!'
                echo 'Ahoy'
            }
        }
    }
}

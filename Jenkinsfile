pipeline {
    agent any
    stages {
        stage ('test') {
            when {
                not {
                    anyOf {
                        changelog '\\[skip-ci\\]'
                        changelog '\\[ci-skip\\]'
                    }
                }
            }
            steps {
                echo 'Hi!!'
                echo 'Ahoy'
            }
        }
    }
}

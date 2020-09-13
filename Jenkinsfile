pipeline {
    agent any
    stages {
        stage ('test') {
            when {
                not {
                    changelog '\\[skip-ci\\]'
                    //  changelog '.*^.*\\[skip-ci\\].+$'
                }
            }
            steps {
                echo 'Hi!!'
                echo 'Ahoy'
            }
        }
    }
}

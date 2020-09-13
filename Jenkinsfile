pipeline {
    agent any
    stages {
        stage ('test') {
            when {
                // not {
                    // skip if commit message has [skip-ci] or [ci-skip]
                    changelog '.*^\\[skip-ci\\] .+$'
                // }
            }
            steps {
                echo 'Hi!!'
                echo 'Ahoy'
            }
        }
    }
}

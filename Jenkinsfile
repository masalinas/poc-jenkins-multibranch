pipeline {
    agent any

    stages {
        stage("Evaluate Master") {
            when {
                branch "master"
            }
            steps {
                sh 'echo Master pipeline executed'
            }
        }

        stage("Evaluate Develop") {
            when {
                branch "develop"
            }
            steps {
                sh 'echo Develop pipeline executed'
            }
        }
    }
}

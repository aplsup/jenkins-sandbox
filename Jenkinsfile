pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                maven('clean')
                maven('install')
            }
        }

    }
}
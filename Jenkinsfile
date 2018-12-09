pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                step {
                    maven('clean')
                    maven('install')
                }
            }
        }

    }
}
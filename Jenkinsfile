pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                maven {
                    goals('clean')
                    goals('install')
                    localRepository(LocalRepositoryLocation.LOCAL_TO_WORKSPACE)
                    properties(skipTests: true)
                    mavenInstallation('Maven 3.1.1')
                    providedSettings('central-mirror')
                }
            }
        }

    }
}
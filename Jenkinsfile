pipeline {
    agent {
         docker { image 'node:16.13.1-alpine' }
    }
   
    stages {
        stage('Version') {
            steps {
                sh 'node --version'
            }
        }

        stage("Build") {
            steps {
                echo 'building the applicattion..'
                echo 'test webhook..'
            }
        }
        stage("Test") {
            steps {
                echo 'testing the applicaztion..'
            }
        }
        stage("Deploy") {
            steps {
                echo 'deploying the application..'
            }
        }
    }
}

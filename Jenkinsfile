pipeline {
    agent any

    triggers {
        pollSCM('H/2 * * * *')
    }

    stages {

        stage('Checkout') {
            steps {
                echo 'Using SCM checkout from Jenkins job config'
            }
        }

        stage('Build') {
            steps {
                echo 'Building frontend project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests (mock)...'
            }
        }

        stage('Code Coverage') {
            steps {
                echo 'Generating code coverage (mock)...'
            }
        }

        stage('SonarQube Analysis') {
            steps {
                echo 'Running SonarQube analysis (mock)...'
            }
        }

        stage('Deliver') {
            steps {
                echo 'Packaging project...'
            }
        }

        stage('Deploy to Dev') {
            steps {
                echo 'Deploying to Dev...'
            }
        }

        stage('Deploy to QAT') {
            steps {
                echo 'Deploying to QAT...'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to Staging...'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying to Production...'
            }
        }
    }
}

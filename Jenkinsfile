pipeline {
    agent any

    triggers {
        pollSCM('H/2 * * * *')
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello from Jenkins!'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...hiiiiiiiiiiiiiiiii'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing project...'
            }
        }
    }
}

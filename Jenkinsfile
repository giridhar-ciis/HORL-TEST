pipeline {
    agent any

    stages {
        stage('Cleanup') {
            steps {
                echo 'Clean Workspace..'
            }
        }
        stage('Build') {
            steps {
                echo 'Code Build'
            }
        }
        stage('Notification') {
            steps {
                echo 'Notify'
            }
        }
    }
}
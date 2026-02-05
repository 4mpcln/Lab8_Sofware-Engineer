pipeline {
    agent any

    stages {
        stage('Check environment') {
            steps {
                echo 'Checking Jenkins built-in agent'
                sh 'uname -a'
            }
        }

        stage('Run simple command') {
            steps {
                echo 'Running simple shell command'
                sh 'echo Hello Jenkins'
            }
        }
    }
}

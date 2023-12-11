pipeline {
    agent any

    stages {
        stage('check out') {
            steps {
                echo 'check out'
            }
        }
        stage('build') {
            steps {
                echo 'build'
            }
        }
        stage('test') {
            steps {
                python script.py
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy'
            }
        }
    }
}

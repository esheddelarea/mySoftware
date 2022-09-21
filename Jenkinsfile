properties([pipelineTriggers([pollSCM('30 * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
             git 'https://github.com/esheddelarea/mySoftware.git'
             sh 'python3 click.py'
            }
        }
    }
}

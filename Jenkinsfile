pipeline {
    agent any 
    stages {
        stage('build') {
            steps {
                sh 'chmod a+x jenkins/prod.sh'
                sh './jenkins/prod.sh'
            }
        }
        stage('test'){
            steps{
                sh 'echo'
            }
        }
    }
}
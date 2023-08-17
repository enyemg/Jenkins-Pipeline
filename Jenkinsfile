pipeline {

agent any
    stages {
        stage ('Say hello and tell us who you are') { 
            steps{
                sh 'echo "This is our second jeckins pipeline script"'
                sh 'whoami'
            }
        }
        stage ('Check git version') {
            steps{
                sh 'git --version'
            }    
        }
        stage ('Docker') {
            steps{
                sh 'docker --version'
            }
        }    
    }
}

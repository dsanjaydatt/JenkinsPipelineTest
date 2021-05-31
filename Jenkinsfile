pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello! Welcome to Jenkins Pipeline test'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        
        stage('Deploy') {
            steps {
               sh "/usr/bin/perl -w check.pl "
            }
        }
        
        stage('Release') {
            steps {
                echo 'Releasing'
            }
        }
    }
}

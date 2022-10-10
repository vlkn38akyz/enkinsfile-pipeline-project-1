pipeline {
    agent any
    stages {
        stage('run1') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python --version'
                sh 'python pipline.py'
                
            }   
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello'
            }
        }
    }
}

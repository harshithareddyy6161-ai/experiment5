pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'ls -la'
                sh 'javac HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}

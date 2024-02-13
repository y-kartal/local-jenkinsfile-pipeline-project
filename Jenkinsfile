pipeline {
    agent any
    environment {
        JAVA_HOME = '/path/to/your/jdk'
    }
    stages {
        stage('Build') {
            steps {
                sh 'javac Hello.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java Hello'
            }
        }
    }
}

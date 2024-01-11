pipeline {
    agent any

    stages {
        stage('Java') {
            steps {
                script {
                    tool name: 'JAVA11', type: 'jdk'
                    sh 'java -version'
                }
            }
        }
        stage('maven') {
            steps {
                script {
                    tool name: 'maven', type: 'maven'
                    sh 'mvn -v'
                }
            }
        }
        stage('mvn clean') {
            steps {
                script {
                    tool name: 'maven', type: 'maven'
                    sh 'mvn clean'
                }
            }
        }
        stage('mvn compile') {
            steps {
                script {
                    tool name: 'maven', type: 'maven'
                    sh 'mvn compile'
                }
            }
        }
        stage('mvn test') {
            steps {
                script {
                    tool name: 'maven', type: 'maven'
                    sh 'mvn test'
                }
            }
        }
        stage('mvn package') {
            steps {
                script {
                    tool name: 'maven', type: 'maven'
                    sh 'mvn package'
                }
            }
        }
    }
}


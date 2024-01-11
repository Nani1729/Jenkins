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
    }
}


pipeline {
    agent any

    stages {
        stage('fetch the code from github') {
            steps {
                echo 'fetch the code from github'
            }
        }
        stage('mavenBuild') {
            steps {
                echo 'mavenBuild'
            }
        }
        stage('Sonar') {
            steps {
                echo 'Sonar'
            }
        }
        stage('Nexus') {
            steps {
                echo 'Nexus'
            }
        }
    }
}

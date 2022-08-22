pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git url: 'https://github.com/Lucas-knut/Jenkins-Maven'
                withMaven {
                    sh 'mvn clean install'
    }            }
            }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        }
    }

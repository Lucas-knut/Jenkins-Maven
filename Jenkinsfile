pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git url: 'https://github.com/Lucas-knut/Jenkins-Maven'
                withMaven (
                    maven: 'maven-3',
                ){
                    sh 'mvn clean install'
                }
            }
        }
    }
}

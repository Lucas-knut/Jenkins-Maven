pipeline {
    agent any

    stages {
        stage('Maven install') {
            steps {
                withMaven (
                    maven: 'maven-3',
                ){
                    sh 'mvn clean install'
                }
            }
        }
    }
}

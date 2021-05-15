pipeline {
    agent any

    stages {
        stage('GIT Clone') {
            steps {
                git 'https://github.com/abhatech/maven-helloworld.git'
            }
        }
        stage('Maven Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}

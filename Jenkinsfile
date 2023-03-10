pipeline {
    agent any

    stages {
        stage("git checkout maven pom file"){
            steps{
                git 'https://github.com/Mahadevlt01/repo1.git'
            }
        }
        stage("Maven Build"){
            steps{
                sh "mvn package"
            }
        }
    }
}

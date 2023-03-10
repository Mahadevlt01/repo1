pipeline {
    agent any

    stages {
        stage("git checkout maven pom file"){
            steps{
                git 'https://github.com/Mahadevlt01/repo1/mvn_sample'
            }
        }
        stage("Maven Build"){
            steps{
                sh "mvn package"
            }
        }
    }
}

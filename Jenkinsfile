pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                sh "docker build -t elede99/pokedex-flask:${env.BUILD_NUMBER} ."
            }
        } 
    }
}

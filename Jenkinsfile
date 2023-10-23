pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                sh "docker build -t franvalle/pokedex-flask:${env.BUILD_NUMBER} ."
            }
        }
      }
}

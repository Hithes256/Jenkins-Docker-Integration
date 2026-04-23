pipeline{
    agent any
    stages{
        stage("Build image"){
            steps{
              bat 'docker build -t pracmy .'
            }
        }
        stage("Run image"){
            steps{
              bat 'docker run pracmy'
            }
        }
    }
}

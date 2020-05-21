pipeline{
    agent any
    stages{
        stage ("Maven Build"){
            steps{
                git url: https://github.com/anil23489/game-of-life.git
                bat '''
                mvn clean install
                '''
            }
        }
    }
}

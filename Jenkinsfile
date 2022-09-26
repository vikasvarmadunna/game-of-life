pipeline{
    agent any
    stages{
        stage('test'){
            steps{
        sh "echo hello"
        }
        }
        stage('learning'){
            steps{
        git url: 'https://github.com/vikasvarmadunna/game-of-life.git', branch: 'amazon'
        }
        }
    }
}


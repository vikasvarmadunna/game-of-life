pipeline{
    agent any
    stages{
        step('test'){
        sh "echo hello"
        }
        step('learning'){
        git url: https://github.com/vikasvarmadunna/game-of-life.git, branch: 'amazon'
        }
    }
}


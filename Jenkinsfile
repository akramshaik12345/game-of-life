pipeline {
    agent any
    stages {
        stage ( 'code checout') {
            steps {
                git 'https://github.com/akramshaik12345/game-of-life.git'
            }
        }
        stage ('build') {
            steps {
                bat 'mvn test'
            }
        }
    }
}

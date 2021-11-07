pipeline{
    agent any
    stages {
        stage("git"){
            steps{
                git credentialsId: 'git_credentials', url: 'https://github.com/saurabh15-hub/Calculator.git'
            }
        }
    }
    
}

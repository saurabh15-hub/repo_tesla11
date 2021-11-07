pipeline{
    agent any
    stages{
        stage(git){
            steps{
                git branch: 'feature', credentialsId: 'feature_cr', url: 'https://github.com/saurabh15-hub/repo_tesla.git'
            }
        }
    }
}

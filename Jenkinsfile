pipeline{
    agent any
    stages{
        stage('Deploy'){
            options{
                retry(3)
            }
            steps{
                ping "www.google.com"
            }
        }
    }
}
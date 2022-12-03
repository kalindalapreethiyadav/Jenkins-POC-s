pipeline{
    agent dev
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
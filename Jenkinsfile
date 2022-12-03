pipeline{
    agent any
    stages{
        stage{
            options{
                retry(3)
            }
            steps{
                ping "www.google.com"
            }
        }
    }
}
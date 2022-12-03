pipeline{
    agent dev
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
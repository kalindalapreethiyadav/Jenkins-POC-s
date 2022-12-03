pipeline
{
    agent any
    stages("Testing")
    {
        stage("build")
        {
            steps{
                echo "building the code"
            }
        }

        stage("test")
        {
            steps{
                echo "testing the code"
            }
        }
        stage("upload")
        {
            steps{
                echo "package & upload the code"
            }
        }
    }

}
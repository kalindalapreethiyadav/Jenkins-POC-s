pipeline
{
    agent any
    parameters{
        string (name:'NAME', defaultValue:'preethi',description: 'Enter your Name:')
        test(name:'Role', defaultValue:'devopsEngineer\nApplication Devloper', description: 'Enter your Role please:')
        choice(name:'Company',choices:'IBM\nAccenture\nCTS\nDelotte\nTCS', description:'Select the comapany:')
        file(name:'File',description:'Select the file to upload:')
        password(name:'Password',defaultValue:'SECRET_password', description:'A secret password')
        booleanParam(name:'Toggle', defaultValue:true, description:'Toggle the Value')
   }

    stages
    {
        stage('String')
        {
            steps{
                echo "building the code"
            }
        }
        stage('text')
        {
            steps{
                echo "testing the code"
            }
        }
        stage("choice")
        {
            steps{
                echo "package & upload the code"
            }
        }
        stage('file')
        {
            steps{
                echo "file uploaded"
            }
        }
        stage('password')
        {
            steps{
                echo "password entered secret"
            }
        }
        stage('booleanParam')
        {
            steps{
                echo "boolen value"
            }
        }
    }

}
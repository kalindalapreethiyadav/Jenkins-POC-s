pipeline
{
    agent any
    parameters{
        string (name:'user', defaultValue:'preethi',description: 'Enter your Name:')
        text(name:'Role', defaultValue:'devopsEngineer\nApplication Devloper', description: 'Enter your Role please:')
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
                echo "String $user"
            }
        }
        stage('text')
        {
            steps{
                echo "Text $Role"
            }
        }
        stage("choice")
        {
            steps{
                script{
                    if(Role == 'devopsEngineer')
                    {
                        echo "Select the company $Company"
                    }
                }
                echo "choice $Company"
            }
        }
        stage('file')
        {
            steps{
                echo "file uploaded $File"
            }
        }
        stage('password')
        {
            steps{
                echo "password entered secret $Password"
            }
        }
        stage('booleanParam')
        {
            steps{
                script{
                    if(Toggle)
                    {
                          echo "boolen value $Toggle"
                    }
                    else
                    {
                         echo "boolen value $Toggle"
                    }

                }
              
            }
        }
    }

}
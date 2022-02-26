pipeline {
   agent 
    { 
        node 
        { 
            label 'master' 
        } 
    } 

    stages
    {
        stage('Read demo file')
        {
            steps{
                cat Telugu
            }
        }
    }
}

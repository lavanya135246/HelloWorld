pipeline {
   agent 
    { 
        node 
        { 
            label 'master' 
        } 
    } 
   
   parameters {
        string(name: 'FileName', defaultValue: 'Telugu', description: 'Please enter a file name')
   }

    stages
    {
        stage('Read Telugu')
        {
            steps{
               sh "cat ${params.FileName}"
            }
        }
       stage('Read Hindi')
        {
            steps{
                sh "cat ${params.FileName}"
            }
        }
    }
}

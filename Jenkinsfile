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
        stage('Read Telugu')
        {
            steps{
                sh 'cat Telugu'
            }
        }
       stage('Read Hindi')
        {
            steps{
                sh 'cat Hindi'
            }
        }
    }
}

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
        choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')
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
       stage('Print from choice')
       {
          steps{
             echo "Choice parameter selected is: ${params.CHOICE}"
          }
       }
    }
}

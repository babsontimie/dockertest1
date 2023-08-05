pipeline{
    agent any
    {
        dockerContainer{
           image 'ubuntu:latest'
       }
    }
     option {
         newContainerPerStage()
     }
      stages{
        stage('Build'){
          steps{
           sh '''

             printenv
               '''
        }
        }
        stage('Test'){
          steps{
           sh '''
     printenv
                
               '''
          }
        }             
        stage('Deploy'){
          steps{
           sh '''
               pwd && ls -ltra
                
               '''
          }
        }


}
}

pipeline{
    agent any
    //{
//        dockerContainer{
//            image 'ubuntu:latest'
//        }
//    }
      stages{
        stage('Build'){
          steps{
           sh '''
               cat /etc/lsb-release
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

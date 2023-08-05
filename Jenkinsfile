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
                
               '''
        }
        }
        stage('Test'){
          steps{
           sh '''
               cat /etc/lsb-release
                
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

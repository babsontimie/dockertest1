pipeline{
    agent{
        dockerContainer{image 'centos:latest'}
    }
      stages{
        stage('Build'){
          steps{
           sh '''
               cat /etc/hosts
                
               '''
        }
        }
        stage('Test'){
          steps{
           sh '''
               sudo updatedb
                
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

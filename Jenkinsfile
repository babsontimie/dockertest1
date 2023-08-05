pipeline{
    agent{
        docker{image 'centos:centos7.9.2009'}
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

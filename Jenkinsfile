pipeline{
    agent{
        docker { image 'centos:centos7.9.2009' 
               }
    }
      stages{
        stage('Build'){
          step {
           sh '''
               cat /etc/hosts
                
               '''
        }
        }
        stage('Test'){
          step{
           sh '''
               sudo updatedb
                
               '''
          }
        }             
        stage('Deploy'){
          step{
           sh '''
               pwd && ls -ltra
                
               '''
          }
        }


}
}

pipeline{
    agent{
        docker { image 'centos:centos7.9.2009' 
               }
    }
      stages{
        stage('Build'){
           sh '''
               cat /etc/hosts
                
               '''
        }
        stage('Test'){
           sh '''
               sudo updatedb
                
               '''
        }             
        stage('Deploy'){
           sh '''
               pwd && ls -ltra
                
               '''
        }


}
}

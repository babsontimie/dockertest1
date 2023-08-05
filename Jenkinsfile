pipeline{
    agent{
        docker {
            image 'ubuntu:latest'
        }
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

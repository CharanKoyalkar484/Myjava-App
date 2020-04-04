pipeline
{
  agent any
  stages
  {
    stage('continuousDownload') 
    {
      steps
      {
       git 'https://github.com/CharanKoyalkar484/Myjava-App.git'
      }
    }
    stage('continuousBuild')
    {
      steps
      {
        sh label: '', script: 'mvn package'
      }
    }
  }
}

    
    
    
    
    
    
    
    
    
    
    
    
    
}

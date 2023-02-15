pipeline{
  agent{
    docker { image 'nginx' }
  }
  
  stages{
    stage('Test'){
      steps{
        sh 'echo CIAO A TUTTI'
      }
    }
  }
}

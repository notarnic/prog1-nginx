pipeline{
  agent{
    docker { image 'nginx' }
  }
  
  stages{
    stage('Test'){
      steps{
        sh 'wget -O index.html https://raw.githubusercontent.com/notarnic/prog1-nginx/main/index.html?token=GHSAT0AAAAAAB5VDETYUNND7J7YTED72QXAY7M4MOA'
        sh 'cp index.html /usr/share/nginx/html/index.html'
      }
    }
  }
}

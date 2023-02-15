pipeline{
  agent{
    docker { image 'nginx' }
  }
  
  stages{
    stage('Test'){
      steps{
        sh 'wget -O index.html https://raw.githubusercontent.com/notarnic/prog1-nginx/main/index.html?token=GHSAT0AAAAAAB5VDETYBVI36JHEJ7B5F6ZEY7M4IYA'
        sh 'cp index.html /usr/share/nginx/html/index.html'
      }
    }
  }
}

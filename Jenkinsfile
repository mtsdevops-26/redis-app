pipeline{
    agente any
    stage('build omage docker'){
        steps{
        sh 'docker build -t devops/app .'
     
        }

    }
      stage('subir docker compose'){
        steps{
            sh 'docker-compose up'
        }
      }
}
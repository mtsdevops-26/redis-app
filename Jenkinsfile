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
      stage('sleep container')
      steps{
        sh 'sleep 10'
      }
        stage('teste app')
      steps{
        sh 'teste-app.sh' 
    }    

}
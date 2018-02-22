pipeline{

   agent any
   stages {

      stage('Docker Compose Build'){

         agent any
         steps {
            sh 'docker-compose build'
         }

     }
      stage('Run images in Docker Compose'){

         agent any
         steps {

            sh 'docker-compose up -d'

         }

      }

 }

}

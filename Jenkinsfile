pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'test'//commit  sjnj
            }
        }
        stage('Test') {
            steps {
                echo 'this is test'//comment aaaaaa bbbbbb
            }
        }
        stage('Deploy') {
            steps {
                echo 'This is deploy'//this is deploy stage
               
            }
        }
         
        
         }
       post//post
           {
              always
              {
                 emailext body: 'summary', replyTo: 'madasaakanksha0@gmail.com', subject: 'jenkinspipeline', to: 'madasaakanksha0@gmail.com'//this is post line
              }
           }
}


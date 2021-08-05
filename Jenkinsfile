pipeline {

    agent any
      tools {
          jdk ("jdk1.8.0_291")
          

    stages {

        stage ('Compile Stage') {



            steps 

              {

                   bat label: '', script: 'mvn compile'

                }

            }

        
        stage ('Testing Stage') {



            steps 

                 {

                    bat label: '', script: 'mvn test'

                }

            

        }





        stage ('Package Stage') {

            steps 

                {

                    bat label: '', script: 'mvn package'

                }

            }

        

    }

}

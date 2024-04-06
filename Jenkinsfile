pipeline{
   agent any
   
   stages{
      stage('Build')
       {
         steps
         {
             echo 'Build App'
         }
       }
      stage('Test')
       {
         steps
         {
             echo 'Test App'
         }
       }
       stage('Deploy')
       {
         steps
         {
             echo 'App Deployed'
         }
       }
  }
  post{
     always{
        emailext body:'Created',subject:'Pipeline Status',to:'saurabh.prakash1890@gmail.com'
     } 
}

}

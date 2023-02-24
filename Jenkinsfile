pipeline{
  agent any 
  stages{
    stage('Test'){
      step{
        echo "Hello world"
        input "Do you like to proceed?"
      }
    }
    stage('production'){
      step{
        echo "Successfully production Tested"
      }
    }
  }
} 

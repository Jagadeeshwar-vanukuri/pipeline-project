pipeline{
  agent any 
  stages{
    stage('Test'){
      steps{
        echo "Hello world"
        input "Do you like to proceed?"
      }
    }
    stage('production'){
      steps{
        echo "Successfully production Tested"
      }
    }
  }
} 

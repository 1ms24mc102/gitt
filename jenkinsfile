pipeline{
  agent any
  stages{
    stage('Checkout'){
      steps{
          git branch:'main', url:'https://github.com/1ms24mc102/gitt'
      }
    }
    stage('Build'){
      steps{
          echo "Building..."
      }
    }
    stage('Test'){
      steps{
          echo "Testing..."
      }
    }
  }
}

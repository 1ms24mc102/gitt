pipeline{
  agent any
  tools{
    jdk 'jdk21'
  }
  stages{
    stage('Checkout'){
      steps{
          git branch:'main', url:'https://github.com/1ms24mc102/gitt'
      }
    }
    stage('Compile'){
      steps{
          echo "Compiling..."
          sh 'javac Hello.java'
      }
    }
    stage('Run'){
      steps{
          echo "Running..."
          sh 'java Hello'
      }
    }
  }
}

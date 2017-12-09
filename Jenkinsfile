pipeline{
agent any
  stages{
    stage('Build'){
      steps{
        bat 'echo "Build stage"'
        bat 'dir'
      }
    }
    stage('Development'){
      steps{
        bat 'echo "Development stage"'
      }
    }
    stage('Staging'){
      steps{
        bat 'echo "Staging stage"'
      }
    }
  }
}

pipeline{
agent any
  stages{
    stage('Build'){
      steps{
        bat 'echo "Build stage"'
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
    stage('Production'){
      steps{
        bat 'echo "Productions stage"'
      }
    }
  }
  post{
        always{
                bat 'echo "Result"'
                junit 'build/reports/**/*.xml'
              }
      }
}

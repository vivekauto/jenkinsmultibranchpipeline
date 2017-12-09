pipeline{
agent any
  stages{
    stage('Build'){
      steps{
        bat 'echo "Build stage"'
      }
    }
  }
    post{
        always{
                junit 'build/reports/**/*.xml'
              }
        }
}
pipeline{
    agent any
    stages{
        stage('Build'){
          steps{
          echo 'Build Stage'
          }
      }
      stage('Clean'){
          steps{
          sh 'mvn clean'
          }
      }
    }
}

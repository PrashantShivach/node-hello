pipeline{
  agent any
  stages{
    stage('clone'){
      steps{
      git branch: 'deploy', url: 'https://github.com/PrashantShivach/node-hello.git'
      }}
    stage('run'){
      steps{
     sh '''npm pack
npm start'''
      }}
  }
}

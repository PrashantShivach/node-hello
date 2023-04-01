pipeline{
  agent any
  stages{
    stage('clone'){
      step{
      git branch: 'deploy', url: 'https://github.com/PrashantShivach/node-hello.git'
      }}
    stage(run){
      step{
     sh '''npm pack
npm start'''
      }}
  }
}

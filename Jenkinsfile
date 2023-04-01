pipeline{
  agent any
  stages{
    stage('clone'){
      git branch: 'deploy', url: 'https://github.com/PrashantShivach/node-hello.git'
    }
    stage(run){
     sh '''npm pack
npm start'''
    }
  }
}

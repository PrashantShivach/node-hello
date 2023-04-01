pipeline{
  agent any
  stages{
    stage('clone'){
      git branch: 'testing', url: 'https://github.com/PrashantShivach/node-hello.git'
    }
    stage(run){
     sh '''npm pack
npm start'''
    }
  }
}

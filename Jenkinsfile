pipeline {

  agent: any
 
  stages{
  
    stage("Build") {
      qmake TestCppGithub.pro
      make
    }
  }
  
}

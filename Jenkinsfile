pipeline {

  agent any
 
  stages{
  
    stage("Build") {
      steps {
        echo "Building ..."
      }
      steps{
              qmake TestCppGithub.pro
              make

      }
    }
  }
  
}

pipeline{
agent any
stages{
    stage("SCM")
    steps{
    echo 'stage start'
    git 'https://github.com/VikrantSinghBhadauriya/simple-java-maven-app-1.git'
    }
}
    stage("Testing Stage"){
      steps{
    
    echo 'In Test stage'
      }
    }
}
node{
  stage('SCM Checkout'){
      git 'https://github.com/abdulmujib6/TestProject'
  }
  stage(Compile-Package){
     sh 'mvn package'
  }
}

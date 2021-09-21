node{
  stage ('SCM Checkout'){
    git 'https://github.com/victorandruscagit/PIPA'
  }
  stage ('Compile-Package'){
   sh 'mvn package'
  }
}

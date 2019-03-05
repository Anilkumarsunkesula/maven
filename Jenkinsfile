node{
   stage('SCM Checkout'){
      git 'https://github.com/RaviBeta7/maven'
   }
   stage('Compile-Package'){
        sh "mvn package"
    }
}

node{
   stage('SCM Checkout'){
      git 'https://github.com/RaviBeta7/maven'
   }
   stage('Compile-Package'){
        sh "mvn package"
    }
   stage('sleep'){
         sh "sleep 5s"
   }
   stage('list'){
         sh "ls"
   }
}

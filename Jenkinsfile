node{
  stage('SCM Checkout'){
    git 'https://github.com/PriyaBhardwaj/cucumberbasic'
  }
  stage('Compile Package'){
    def = tool name: 'MAVEN', type: 'maven'
    sh ="${mvnHome}/bin/mvn package"
  }
}
    

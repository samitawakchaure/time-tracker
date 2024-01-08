node{
  stage('SCM Checkout'){
    git 'https://github.com/samitawakchaure/time-tracker'
  }
  stage('Complie-package'){
        def mvnHome = tool name: 'maven-3', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
        }
}

node {
  stage ('SCM checkout') {
    git url: 'https://github.com/frescoplaylab/JenkinsDeliveryPipeline.git'
  }
  stage ('maven clean') {
    sh "mvn clean verify"
  }
  stage ('maven compile') {
      sh "mvn package"
  } 
}

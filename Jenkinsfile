node{
  stage('SCM checkout'){
    git 'https://github.com/steffyelza/jenkinspractise'
  }
  stage('Compile-Package'){
  sh 'mvn package'
  }
}

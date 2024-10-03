node{
  stage('SCM Checkout'){
    git 'https://github.com/praveen9065/my-app.git'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}

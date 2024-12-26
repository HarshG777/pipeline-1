node{
  stage('Build'){
    echo "Building"
  }
  stage('Test'){
    echo "Testing"
  }

  if(currentBuild.currentResult=="SUCCESS"){
    echo "Looks Good"
  }else{
    echo "FAIL"
  }
}

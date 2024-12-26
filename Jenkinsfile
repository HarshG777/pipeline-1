node{
  stage('Build'){
    echo "Building"
  }
  stage('Test'){
    echo "Testing"
  }

  if(currentBuild.result=='SUCCESS'){
    echo "Looks Good"
  }else{
    echo "FAIL"
  }
}

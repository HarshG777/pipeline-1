pipeline{
  agent any
  stages{
    stage('Breakfast'){
      steps{
        echo "Having Breakfast"
      }
    }
    stage('Workout'){
      steps{
        echo "Going for workout"
      }
    }
    stage('Study'){
      steps{
        echo "Doing Study"
      }
    }
    stage("Familytime"){
      steps{
        echo "Having familytime"
      }
    }
    stage("Playing"){
      steps{
        echo "Playing"
      }
    }
  }
  post{
    success{
      echo  "Success"
    }
    failure{
      echo "Fail"
    }
  }
}



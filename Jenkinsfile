Pipeline{
  agent none
  stages{
    stage('init'){
      steps{
        sh 'terraform init -upgrade -no-color'
      }
    }
  stage('validate'){
      steps{
        sh 'terraform validate -no-color'
      }
    }
  stage('plan'){
      steps{
        sh 'terraform validate -no-color'
      }
    }
  stage('apply'){
      steps{
        sh 'terraform apply --auto-approve -no-color'
      }
    }
}

pipeline {
agent any 
  stages {
    stage('Build ec2') {
      steps {
        sh "aws cloudformation create-stack --stack-name laxmistack --template-body file://ec2-cloudformation.yaml --region 'us-east-1'"
      }
    }
  }

}


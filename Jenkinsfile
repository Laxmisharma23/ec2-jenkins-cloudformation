pipeline {
agent any 
  stages {
    stage('Hello ec2') {
      steps {
        sh "aws cloudformation create-stack --stack-name laxmiEc2Stack --template-body file://ec2-instance.yaml --region 'us-east-1'"
      }
    }
  }

}

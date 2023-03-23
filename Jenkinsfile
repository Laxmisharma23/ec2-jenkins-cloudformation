pipeline {
agent any 
  stages {
    stage('Hello ec2') {
      steps {
        sh "aws cloudformation create-stack --stack-name laxmiEc2StackTest --template-body file://ec2-instance.yaml --region 'us-east-1'"
      }
    }
  }

}

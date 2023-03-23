pipeline {
agent any 
  stages {
    stage('Build ec2') {
      steps {
        sh "aws cloudformation create-stack --stack-name laxmis3stack1 --template-body file://ec2-cloudformation.json --region 'us-east-1'"
      }
    }
  }

}


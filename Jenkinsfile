pipeline {
agent any 
  stages {
    stage('Build ec2') {
      steps {
        sh "aws cloudformation create-stack --stack-name laxmistack20 --template-body file://ec2-s3.yaml --region 'us-east-1'"
      }
    }
  }

}


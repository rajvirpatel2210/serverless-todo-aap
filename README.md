npm i -g serverless && serverless


1. https://www.serverless.com/framework/docs/tutorial pefering that link for serverless setup
2. created aws account 
3. https://www.youtube.com/watch?v=KngM5bfpttA&ab_channel=Serverless for the IAM
4. setup aws-cli into system using these "msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi" command and configure IAM user using "aws configure"
5. setup roles and permisson for IAM user
6. setup local dynamodb and offline server
7. facing issue with dynamodb so it was resolved using that link https://www.serverless.com/plugins/serverless-offline  
8. taking other references code
9. testing local code
10. deploying code using "sls deploy" 



 https://ad00kbytbh.execute-api.us-east-1.amazonaws.com/dev/todos
  GET - https://ad00kbytbh.execute-api.us-east-1.amazonaws.com/dev/todos
  GET - https://ad00kbytbh.execute-api.us-east-1.amazonaws.com/dev/todos/{id}
  PUT - https://ad00kbytbh.execute-api.us-east-1.amazonaws.com/dev/todos/{id}
  DELETE - https://ad00kbytbh.execute-api.us-east-1.amazonaws.com/dev/todos/{id}"# serverless-todo-aap" 

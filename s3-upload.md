# S3 Upload Test
Created a file in CloudShell, uploaded it to S3, and verified it.

Commandds:
touch hello.txt
echo "Hello from AWS CloudShell" > hello.txt
aws s3 mb s3://andrei-aws-practice-83921
aws s3 cp hello.txt s3://andrei-aws-practice-83921
aws s3 ls s3://andrei-aws-practice-83921

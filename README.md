# github-to-lambda
This demo updates a lambda function: github-to-lambda-staging directly from the AWS CodeBuild with procedure
(1) pip install pandas in lib directory (-t lib)
(2) zip all the files in lib directory to create deployment_package.zip
(3) add the lambda_function.py into the deployment_package.zip
(4) Update the lambda function: github-to-lambda-staging with the deployment_package.zip by AWS CodeBuild directly

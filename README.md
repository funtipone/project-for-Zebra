

# Steps to be followed to run the terraform script

1. Enter your access and secret key details in s3.tf file
2. Change the bucket name in s3.tf
3. Go to code build and create new project
4. In codebuild project, there is a feature to connect to select github source control and add github repository url.
5. Run the codebuild build and terraform will create bucket and upload "hello.txt" in S3 bucket

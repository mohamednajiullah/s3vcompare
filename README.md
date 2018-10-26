# S3 Object Version Compare

This shell script allows the user to compare different versions of a S3 Object.

## Requirements

 Please install the following before running the script.
  
 - AWS CLI
 - jq
 - colordiff
 
 
 
 The script also needs the following AWS credentials as environment variables  
 - AWS_ACCESS_KEY_ID
 - AWS_SECRET_ACCESS_KEY
 - AWS_DEFAULT_REGION
 
 Please load these into your terminal manually or using a tool like direnv
 
##Running the script

The script can be run on the terminal directly as ./s3vcompare.

`./s3vcompare bucket_name folder/filename.extension` 

If you intend to use the script a lot then run the following command

`cp s3vcompare /usr/local/bin`

and now you can run the script like a program from anywhere.

`s3vcompare bucket_name folder/filename.extension` 
 
 #### Pull requests are welcome
 
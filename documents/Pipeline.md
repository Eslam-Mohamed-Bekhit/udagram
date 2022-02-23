


## CircleCI
 commit and push  code to the GitHub => GitHub triggers config.yml file => run jobs  :
-  Runs the build Frontend script Then uses AWS CLI to upload  to S3.
- Runs the build Server script => exports  environment variables from CircleCI configuration to a env file => use AWS CLI to upload archive to S3.
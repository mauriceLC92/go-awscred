# go-awscred

## Goals

- Output the AWS credentials available to you based on your `.aws/credentials` file
- Allow you to "apply" the profile of your choice
- When applying the profile, first check if the credentials have expired. If yes, choose to remove them
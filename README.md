# Automate Terraform with GitHub Actions

This repo is a companion repo to the [Automate Terraform with GitHub Actions tutorial](https://developer.hashicorp.com/terraform/tutorials/automation/github-actions).

# S3 backend
# run terraform first from the backend subdir to provision s3 bucket and dynamodb table as initial step
# only then, uncomment s3 backend block and \
# run terraform from the root dir of the repo so it can put state file on s3


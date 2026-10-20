### Pre-requisite

## Below steps need to follow to create pipeline (for first client)
1. Create codestar connection with repository
2. Using "codepipeline/shared-codebuild.yaml" file with cloudformation template create "codepipeline/shared-codebuild-for-terraform" stack
3. Using "per-repo-pipeline.yaml" file with cloudformation template create pipeline for particular client. i.e. "terraform-codepipeline-client-1"

## From second client onwards
1. Create codestar connection with repository
2. Using "per-repo-pipeline.yaml" file with cloudformation template create pipeline for particular client. i.e. "terraform-codepipeline-client-2"


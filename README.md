# gh-envs
Example project for using GitHub Environments and Deployments

## What's in this?
- [semantic-release](https://github.com/semantic-release/semantic-release) for automated versioning and release notes based on commit messages.
- github actions for workflow to go from commit to build to deployments that progress through environments.
- github environments with manual gates for specific environments (i.e. QA doesn't want every release auto deploying and interfering with in-progress testing)

## How to
1. Create a new branch for your commits.  
1. Use [angular conventional commit messages](https://github.com/angular/angular/blob/main/CONTRIBUTING.md#type). e.g. feat: added feature 123. 
1. Create a PR when you're ready for build/tests to run and for it to deploy to an integrated dev environment.
1. Merge to main when you're ready for a github release to be created and for your changes to be available for deployment for QA and later envs.

# gh-envs
Example project for using GitHub Environments and Deployments

## What's in this?
- semantic-release for automated versioning and release notes based on commit messages.
- github actions for workflow to go from commit to build to deployments that progress through environments.
- github environments with manual gates for specific environments (i.e. QA doesn't want every release auto deploying and interfering with in-progress testing)


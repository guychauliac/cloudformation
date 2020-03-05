## cicd_build_from_github_with_buildspec ##

**Description**

CICD pipeline that will get source from github and execute buildspec.yaml provided in the repo

[<img src="../cloudformation-launch-stack.png">](https://console.aws.amazon.com/cloudformation/home?region=eu-west-2#/stacks/new?stackName=stack_name&templateURL=https://s3-eu-west-1.amazonaws.com/guy.chauliac-cloudformation/cicd/cicd_build_from_github_with_buildspec.yaml)

**Parameters**

- **gitURL** : Repository location
- **stage** : Environmental variable that will be created with key=stage value=provided
- **branchOrTag** : Branch or tag from which the build takes place
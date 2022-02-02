# GitHub Actions CI/CD Workflow

</br>

### Setup GitHub environments Ci/Cd workflow pipeline
- [Step by Step Instructions](https://medium.com/@edoter92/github-actions-ci-cd-workflow-b0e970bdacad)
- [Snippets](https://gist.github.com/edo92/32fbb3c4d12b9a6788ba9d6810eb9a83?file=cicd.yml)

</br>

![pull_request](https://raw.githubusercontent.com/edo92/Ci-Cd-Workflow/main/.assets/pull_request.png)
![push](https://raw.githubusercontent.com/edo92/Ci-Cd-Workflow/main/.assets/push.png)

* Create 3 Environments. Development, Staging, Production
![environments](https://raw.githubusercontent.com/edo92/Ci-Cd-Workflow/main/.assets/environments.jpg)

* Enable Request reviewers only on production environment, others leave default config.
* Also you can add environment secret, which is accessible only in production environment
![config](https://raw.githubusercontent.com/edo92/Ci-Cd-Workflow/main/.assets/environments.jpg)
 
* On pull request deploys to development environment
![pull_request_ci](https://raw.githubusercontent.com/edo92/Ci-Cd-Workflow/main/.assets/pull_request_ci.png)


* On push to main deploys to staging than to production which requires manual approval
![push](https://raw.githubusercontent.com/edo92/Ci-Cd-Workflow/main/.assets/pull_request_ci.png)

* Production deployment requires manual approval.
![push](https://raw.githubusercontent.com/edo92/Ci-Cd-Workflow/main/.assets/approval.png)


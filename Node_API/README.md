# Integration with Jenkins CI/CD
- Integration with jenkins requires 4-6 simple steps(Installing Jenkins server,installing requires packages)
- After integration is done and this repo we need to add the Jenkinsfile

# Added Kubernetes cluster to the AWS account

# Workflow/CI/CD

- In Jenkinsfile defines the workflow. I used two branche dev and master ,SO our jenkinsfile will be placed on both thtwo branches and also it will include the when condition to make more dynamic
- Developers will branch off from dev branch and create new branches to make modification to the code. Once done, when merged to dev, pipeline will be triggered and docker image will be build & deployment to dev namespace/environment will take place(it is automatic, no need of manual approval as it is a dev environment).
- But for the prodcution deployment ,Manager need to appove the stage to deploy the code in k8 cluster




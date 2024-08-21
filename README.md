# How to setup AWS EKS with Terraform and Github version control workflow

| ITEM | VALUE | NOTES |
|---|---|---|
Hashicorp's official document | https://developer.hashicorp.com/terraform/tutorials/kubernetes/eks | How to Provision an EKS cluster |
Hashicorp Cloud Platform (HCP) | https://app.terraform.io/ | Where workspace is hosted |
AWS account or subscription based playground | https://aws.amazon.com/ or https://learn.acloud.guru/home | *aCloudguru playgrounds are destroyed nightly<br>*alleviates the stress of AWS costs |
Connect from your laptop| https://docs.aws.amazon.com/eks/latest/userguide/create-kubeconfig.html | From your laptop shell:<br>1. aws configure<br>2. aws eks update-kubeconfig --region region-code --name my-cluster |
| Creating an HCP workspace | Tips:<br> ![images/Workspace auto-apply](workspace_setting_auto_apply.png?raw=true "HCP workspace auto-apply") |
|  |  |

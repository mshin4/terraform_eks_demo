# How to setup AWS EKS with Terraform and Github version control workflow

| ITEM | VALUE | NOTES |
|---|---|---|
Hashicorp's official document | How to Provision an EKS cluster | https://developer.hashicorp.com/terraform/tutorials/kubernetes/eks |
Hashicorp Cloud Platform (HCP) | Where workspace is hosted | https://app.terraform.io/ |
AWS account or subscription based playground | *aCloudguru playgrounds are destroyed nightly<br>*alleviates the stress of AWS costs | https://aws.amazon.com/ or https://learn.acloud.guru/home |
Connect from your laptop | From your laptop shell:<br>1. aws configure<br>2. aws eks update-kubeconfig --region region-code --name my-cluster | https://docs.aws.amazon.com/eks/latest/userguide/create-kubeconfig.html<br><br>MacOS location: /Users/<username>/.kube/config<br>***kubectl and helm uses the kubeconfig for authentication |
Creating an HCP workspace | Tips:<br><br>Workspace setting<br> ![images/Workspace auto-apply](workspace_setting_auto_apply.png?raw=true "HCP workspace auto-apply")<br><br>When creating a workspace, select version control workflow<br><br>Create Variable set<br>(done at Organization level)<br>AWS_ACCESS_KEY_ID<br>AWS_SECRET_ACCESS_KEY<br> |
Install Helm | MacOS<br>brew install helm | https://helm.sh/docs/intro/install/ |
Install K8s Dashboard |  | https://artifacthub.io/packages/helm/k8s-dashboard/kubernetes-dashboard |
How to access K8s Dashboard from laptop|  |  |
|  |  |

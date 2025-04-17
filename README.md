# samcart assessment

## AWS account

ID: 824762106810

Login URL: https://824762106810.signin.aws.amazon.com/console

## Terraform

Very simple TF code, no modules or remote resources needed.

Deployed:

-   VPC
-   Subnets
-   RouteTable & routes & association
-   InternetGateway
-   EKS cluster
-   Node group
-   IAM roles for the cluster & nodes
-   SecurityGroup

## K8s cluster

-   VPN CNI add on installed
-   Istio installed after TF deployment (dimplifies ingress)

## App

Istio sample 'Book Review' app, deployed/redeployed via Github Action/Workflow.

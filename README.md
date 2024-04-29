<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-aws-eks/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraspace EKS with the Terraform Registry Module Example

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

This contains example code based on examples from the Terraform Registry EKS module: [terraform-aws-modules/eks/aws](https://registry.terraform.io/modules/terraform-aws-modules/eks/aws/latest)

## Env Vars

You should configure these env vars:

* AWS_REGION

## Deploy

To deploy:

    terraspace up fargate
    terraspace up managed_node_groups
    terraspace up eks-spot

## Video: EKS Managed Nodes

[![Watch the video](https://uploads-learn.boltops.com/j3vkq0w8tf95m3pfir0b2xw1rqoe)](https://learn.boltops.com/courses/aws-eks/lessons/eks-create-cluster-with-terraform-registry-eks-module-managed-nodes)

Note: Premium video content requires a subscription.

## Video: EKS Fargate

[![Watch the video](https://uploads-learn.boltops.com/hb1dqxvjg54h40uq47ixekfznxw9)](https://learn.boltops.com/courses/aws-eks/lessons/eks-create-cluster-with-terraform-registry-eks-fargate)

Note: Premium video content requires a subscription.

## Video: EKS Spot Cluster

[![Watch the video](https://uploads-learn.boltops.com/b3vuo7j5hrlwxiqjfpp0jpo7i5wd)](https://learn.boltops.com/courses/aws-eks/lessons/eks-create-cluster-with-terraform-registry-eks-module-spot-cluster)

Note: Premium video content requires a subscription.

<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-aws-eks/blob/master/app/stacks/eks-spot/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# EC2 Instance Selector

    ec2-instance-selector --memory 8 --vcpus 2 --cpu-architecture x86_64
    ec2-instance-selector --memory 8 --vcpus 2 --cpu-architecture x86_64 -o table
    ec2-instance-selector --memory 8 --vcpus 2 --cpu-architecture x86_64 -o table-wide --usage-class spot

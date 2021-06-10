# crossplane-aws
The goal of this PoC is to become more familiar with Cross-Plane.
We will utilize previous [EKS PoC](https://github.com/seizadi/eksctl)
to setup EKS cluster with fine-grain IAM for Service Account. Then
follow Cross-Plane directions for setting up 
[AWS Provider Auth](https://github.com/crossplane/provider-aws/blob/master/AUTHENTICATION.md).

Once this is done we will try some common use cases like:
- Setup RDS instance using Static and Dynamic provisioning using the Claim/Resource pattern.
- Setup S3 Bucket

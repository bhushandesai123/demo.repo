# Creating IAM Service Account for AWS Load Balancer Controller

To create an IAM service account for the AWS Load Balancer Controller, run the following command:

```bash
eksctl create iamserviceaccount --cluster=three-tier-cluster --namespace=kube-system --name=aws-load-balancer-controller --role-name AmazonEKSLoadBalancerControllerRole --attach-policy-arn=arn:aws:iam::**<span style="color: red;">626072240565</span>**:policy/AWSLoadBalancerControllerIAMPolicy --approve --region=us-west-2

<font color="green">This text will be green.</font>

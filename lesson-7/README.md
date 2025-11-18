# Status

- Docker image stored in AWS ECR: ✓
- Terraform used to create VPC, Subnets, EKS Cluster, ECR, Backend (S3 + DynamoDB): ✓
- Helm chart used for deployment to EKS: ✓
- ConfigMap and environment variables attached to pod: ✓
- HPA (Horizontal Pod Autoscaler) created and applied: ✓
- Application container deploys successfully, but app exits immediately (Completed), as entrypoint is minimal.

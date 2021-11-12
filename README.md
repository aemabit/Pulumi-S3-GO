### PULUMI - AWS(S3) Using GO

Basic S3 Bucket generator using Go!

#### Requirements

- Install Pulumi
- Configure Pulumi to Use AWS (if your AWS CLI is configured, no further changes are required)
- Install Go


#### Getting Started

- Go to file `Pulumi.dev.yaml`
- Replace the configuration with your aws credentials:
```
config:
  aws:region: <aws-region>
  aws:accessKey: <aws-acceskey>
  aws:secretKey: <aws-secretkey>
```
- Run this command in your terminal `pulumi up` 

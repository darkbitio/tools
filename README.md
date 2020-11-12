## Darkbit Cloud Security Tools

### OpenCSPM (Cloud Security Posture Management framework)

OpenCSPM is an open-source platform that aims to make continuous cloud security posture management easy and scalable. 

[GitHub Repo](https://github.com/OpenCSPM/opencspm)

### AWS Recon (AWS Asset Inventory Collection Tool)

AWS Recon is a command line tool for collecting your entire AWS environment. The tool aims to have better coverage than **AWS Config** while being relatively quick to run, even on large accounts.

[GitHub Repo](https://github.com/darkbitio/aws-recon)

### MKAP (Managed Kubernetes Action Plan)

The Kubernetes Security Action Plan is your guide to the best practices for deploying secure, scalable, and highly available Kubernetes infrastructure.

[Start Action Plan](https://darkbit.io/plan)

### MKIT (Managed Kubernetes Inspector Tool)

This is a tool that collects configuration data from your Cloud Service Provider (CSP) and your Kubernetes cluster and reports on common security risks and vulnerabilities.

[GitHub Repo](https://github.com/darkbitio/mkit)

### AWS S3 DLP

This is a tool to monitor unauthorized or unexpected data transfer from S3 buckets in your org to an external account. It works by triggering CloudWatch rules generated by S3 API `CopyObject` events. These events are then sent to an SNS Topic, which in turn invoke a Lambda function to parse the event and send a Slack notification if objects were copied to an external account.

[GitHub Repo](https://github.com/darkbitio/aws-s3-dlp)


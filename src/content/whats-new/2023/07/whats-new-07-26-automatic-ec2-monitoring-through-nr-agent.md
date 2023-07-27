---
title: 'Automated monitoring of EC2 instances with New Relic'
summary: 'The CloudFormation template provided here automates deployment of New Relic Infrastructure Agent in existing and new ec2 instances in the AWS Account. After successful installation, detailed ec2 instance logs will be sent to New Relic' 
releaseDate: '2023-07-27' 

---
After successfully deplopying this template user will be able to monitor ec2 instances present across multiple regions and AWS Accounts in New Relic. It automates the installation of New Relic Infrastructure Agent in exisiting(before installation of this solution) and new ec2 instances(any instance spinned post installation of this solution). 




**NewRelic Infrastructure Agent installation Logs**



![NewRelic Infrastructure Agent installation Logs](./images/nr_agent_installation_logs.png "EC2 Metrics")




**EC2 Metrics Dashboard in NewRelic**



![EC2 Metrics Dashboard](./images/ec2_metrics_from_agent.png "EC2 Metrics")

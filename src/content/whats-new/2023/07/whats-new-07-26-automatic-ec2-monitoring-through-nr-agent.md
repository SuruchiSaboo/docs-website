---
title: 'Automated monitoring of EC2 instances with New Relic'
summary: 'The CloudFormation template provided here automates deployment of New Relic Infrastructure Agent in existing and new ec2 instances in the AWS Account. After successful installation, detailed ec2 instance logs will be sent to New Relic' 
releaseDate: '2023-07-27' 

---

The ec2 quickstart solution we provide is designed for individuals seeking to enhance observability on AWS EC2 instances within their AWS Account by monitoring host metrics.

After successfully deploying the [cloudformation template](), users will be able to monitor ec2 instances present across multiple regions and AWS Accounts in New Relic. It automates the installation of [New Relic Infrastructure Agent](https://docs.newrelic.com/docs/infrastructure/install-infrastructure-agent/get-started/install-infrastructure-agent/) in existing (before installation of this solution) and new ec2 instances (any instance spinned post installation of this solution). This agent is responsible for sending host metrics to New Relic.  


**NewRelic Infrastructure Agent installation Logs**



![NewRelic Infrastructure Agent installation Logs](./images/nr_agent_installation_logs.png "EC2 Metrics")

The EC2 CloudFormation template has undergone testing to ensure successful deployment. It not only installs the New Relic Infrastructure Agent but also sends installation status of agent to New Relic logs.



**EC2 Metrics Dashboard in NewRelic**

![EC2 Metrics Dashboard](./images/ec2_metrics_from_agent.png "EC2 Metrics")



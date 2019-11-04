---
title: AWS Cloud
published: true
sidebar: mydoc_sidebar
permalink: aws_cloud.html
folder: mydoc
---

{% include links.html %}

## Blogs/Research

* [Hacking Serverless Runtimes: Profiling Lambda, Azure, and more](https://www.blackhat.com/docs/us-17/wednesday/us-17-Krug-Hacking-Severless-Runtimes.pdf)
* [Bypassing and exploiting Bucket Upload Policies and Signed URLs](https://labs.detectify.com/2018/08/02/bypassing-exploiting-bucket-upload-policies-signed-urls/)
* [Cloud basics for pen testers, red teamers, (and defenders)](https://adsecurity.org/wp-content/uploads/2017/07/2017-DEFCON-HackingTheCloud-SteereMetcalf-Final.pdf)
* [Many-faced threats to Serverless security – Hacker Noon](https://hackernoon.com/many-faced-threats-to-serverless-security-519e94d19dba)
* [Elevating Permissions in AWS IAM – CloudSploit](https://blog.cloudsploit.com/privilege-escalation-in-amazon-web-services-cb4837365958)
* [Assume the Worst: Enumerating AWS Roles through ‘AssumeRole’ - Rhino Security Labs](https://rhinosecuritylabs.com/aws/assume-worst-aws-assume-role-enumeration/)
* [AWS Privilege Escalation – Methods and Mitigation](https://rhinosecuritylabs.com/aws/aws-privilege-escalation-methods-mitigation/)
* [Exploiting SSRF in AWS Elastic Beanstalk](https://www.notsosecure.com/exploiting-ssrf-in-aws-elastic-beanstalk/)
* Post Exploitation
  * [Post Exploitation in AWS using Nimbostratus - Cloud Security Operations](https://cloudsecops.com/post-exploitation-in-aws/)
  * [A centralized source of all AWS IAM privilege escalation methods](https://github.com/RhinoSecurityLabs/AWS-IAM-Privilege-Escalation)
  * [AWS Serverless Security Workshop](https://github.com/aws-samples/aws-serverless-security-workshop) - In this workshop, you will learn techniques to secure a serverless application built with AWS Lambda, Amazon API Gateway and RDS Aurora.

## Tools

### S3 Buckets Finder

* [S3Scanner](https://github.com/sa7mon/S3Scanner): Scan for open AWS S3 buckets and dump the contents
* [smiegles/mass3](https://github.com/smiegles/mass3): Quickly enumerate through a pre-compiled list of AWS S3 buckets using DNS instead of HTTP with a list of DNS resolvers and multi-threading.
* [AWS-Scanner](https://github.com/random-robbie/AWS-Scanner): Scans a list of websites for Cloudfront or S3 Buckets
* [goGetBucket](https://github.com/eur0pa/goGetBucket): A penetration testing tool to enumerate and analyse Amazon S3 Buckets owned by a domain.
* [s3-inspector](https://github.com/kromtech/s3-inspector): Tool to check AWS S3 bucket permissions
* [buckets.grayhatwarfare.com](https://buckets.grayhatwarfare.com/): Search for open buckets using online service
* [AWSBucketDump](https://github.com/jordanpotti/AWSBucketDump): Security Tool to Look For Interesting Files in S3 Buckets
* [bucket-stream](https://github.com/eth0izzle/bucket-stream): Find interesting Amazon S3 Buckets by watching certificate transparency logs.
* [CloudScraper](https://github.com/jordanpotti/CloudScraper): Tool to enumerate targets in search of cloud resources. S3 Buckets, Azure Blobs, Digital Ocean Storage Space.

### DFIR

* [aws_ir](https://github.com/ThreatResponse/aws_ir): Python installable command line utiltity for mitigation of host and key compromises.
* [aws-security-automation](https://github.com/awslabs/aws-security-automation): Collection of scripts and resources for DevSecOps and Automated Incident Response Security
* [GDPatrol](https://github.com/ansorren/GDPatrol): A Lambda-powered Security Orchestration framework for AWS GuardDuty
* [awslog](https://github.com/jaksi/awslog): Show the history and changes between configuration versions of AWS resources
* [aws_responder](https://github.com/prolsen/aws_responder): AWS Incident Response Kit (AIRK) - AWS Incident Response

### Defensive

* [ScoutSuite](https://github.com/nccgroup/ScoutSuite): Multi-Cloud Security Auditing Tool
* [prowler](https://github.com/toniblyx/prowler): AWS Security Best Practices Assessment, Auditing, Hardening and Forensics Readiness Tool. It follows guidelines of the CIS Amazon Web Services Foundations Benchmark and DOZENS of additional checks including GDPR and HIPAA (+90).
* [scans](https://github.com/cloudsploit/scans): AWS security scanning checks
* [cloudmapper](https://github.com/duo-labs/cloudmapper): CloudMapper helps you analyze your Amazon Web Services (AWS) environments.
* [cloudtracker](https://github.com/duo-labs/cloudtracker): CloudTracker helps you find over-privileged IAM users and roles by comparing CloudTrail logs with current IAM policies.
* [aws-security-benchmark](https://github.com/awslabs/aws-security-benchmark): Open source demos, concept and guidance related to the AWS CIS Foundation framework.
* [aws_public_ips](https://github.com/arkadiyt/aws_public_ips): Fetch all public IP addresses tied to your AWS account. Works with IPv4/IPv6, Classic/VPC networking, and across all AWS services
* [PMapper](https://github.com/nccgroup/PMapper): A tool for quickly evaluating IAM permissions in AWS.
* [aws-inventory](https://github.com/nccgroup/aws-inventory): Discover resources created in an AWS account.
* [SkyArk](https://github.com/cyberark/SkyArk): SkyArk helps to discover, assess and secure the most privileged entities in AWS
* [lunar](https://github.com/lateralblast/lunar): A UNIX security auditing tool based on several security frameworks
* [cloud-reports](https://github.com/tensult/cloud-reports): Scans your AWS cloud resources and generates reports
* [cs-suite](https://github.com/SecurityFTW/cs-suite): Cloud Security Suite - One stop tool for auditing the security posture of AWS/GCP/Azure infrastructure.
* [cloud-service-enum](https://github.com/NotSoSecure/cloud-sec-wiki) - These script allows pentesters to validate which cloud tokens (API keys, OAuth tokens and more) can access which cloud service.

### Offensive
* [DumpsterDiver](https://github.com/securing/DumpsterDiver): Tool to search secrets in various filetypes.
* [weirdAAL](https://github.com/carnal0wnage/weirdAAL): WeirdAAL (AWS Attack Library)
* [pacu](https://github.com/RhinoSecurityLabs/pacu): The AWS exploitation framework, designed for testing the security of Amazon Web Services environments.
* [aws_pwn](https://github.com/dagrz/aws_pwn): A collection of AWS penetration testing junk
* [cloudjack](https://github.com/prevade/cloudjack): Route53/CloudFront Vulnerability Assessment Utility
* [cloudfrunt](https://github.com/MindPointGroup/cloudfrunt): A tool for identifying misconfigured CloudFront domains
* [mad-king](https://github.com/ThreatResponse/mad-king): Proof of Concept Zappa Based AWS Persistence and Attack Platform
* [cloud-nuke](https://github.com/gruntwork-io/cloud-nuke): A tool for cleaning up your cloud accounts by nuking (deleting) all resources within it
* [cloud-service-enum](https://github.com/NotSoSecure/cloud-sec-wiki) - These script allows pentesters to validate which cloud tokens (API keys, OAuth tokens and more) can access which cloud service.

### Continous Monitoring

* [streamalert](https://github.com/airbnb/streamalert): StreamAlert is a serverless, realtime data analysis framework which empowers you to ingest, analyze, and alert on data from any environment, using datasources and alerting logic you define.
* [security_monkey](https://github.com/Netflix/security_monkey): Security Monkey monitors AWS, GCP, OpenStack, and GitHub orgs for assets and their changes over time.
* [keynuker](https://github.com/tleyden/keynuker): 🔐💥 KeyNuker - nuke AWS keys accidentally leaked to Github

### Miscellaneous

* [kube-hunter](https://github.com/aquasecurity/kube-hunter):  Hunt for security weaknesses in Kubernetes clusters
* [Testing IAM Policies with the IAM Policy Simulator](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_testing-policies.html)

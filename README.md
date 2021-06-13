![portfolio diagram](https://raw.githubusercontent.com/useraddmario/cdond-c3-projectstarter/master/Node_Site.jpg)

[![<useraddmario>](https://circleci.com/gh/useraddmario/autodeploy-pipeline.svg?style=shield)](https://github.com/useraddmario)
# Node.js app deployment to EC2 using Cloudformation, Ansible, and Prometheus

This project's goal was to produce a CI/CD pipeline that builds/tests/security scans/deploys/smoke test a provided sample Node application as well as the accompanying AWS architecture.  This is one of my larger projects and was a part of the Udacity Cloud DevOps course, which was a lot of fun.


### Automation
I used CircleCI to orchestrate the builds/tests/security scans/deploys/smoke test pipeline sequences for the code and AWS infrastructure.


### Infrastructure
Two AWS Cloudformation stacks in combination with Ansible for Node.js/Prometheus Node Exporter installs and configuration.


#### AWS services used include
* S3
* Route53
* CloudFront
* EC2 Instances/Security Groups


### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [Slack](https://slack.com/) - Notification and collaboration software
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool
- [Memstash.io](https://memstash.io/) - Online key-value store

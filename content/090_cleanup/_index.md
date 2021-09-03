---
title: "Cleanup"
chapter: true
draft: false
weight: 90
---

# Workshop Cleanup
{{% notice warning %}}
In order to prevent charges to your account we recommend cleaning up the infrastructure that was created. If you plan to keep things running so you can examine the workshop a bit more please remember to do the cleanup when you are done. It is very easy to leave things running in an AWS account, forget about it, and then accrue charges.
{{% /notice %}}


1. Go to the [Amazon EC2 console](https://console.aws.amazon.com/ec2/) and choose **Instances**. 
1. Select the instance you used for the workshop, and choose **Instance state**, and **Terminate instance**.
1. Choose **Terminate** when prompted for confirmation. 

For more information on terminating AMI instances, see the [AWS help](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/terminating-instances.html)
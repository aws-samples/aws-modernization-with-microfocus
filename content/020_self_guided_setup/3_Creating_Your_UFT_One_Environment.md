---
title: "3. Creating Your UFT One Environment"
chapter: false
weight: 31
---

## Starting the AWS EC2 UFT One Instance

In this section we will explain how to set up your UFT One environment from the [AWS Marketplace] (https://aws.amazon.com/marketplace/pp/prodview-q2d32aqrwglr4).


**UFT One is a desktop application, and should be accesssed via Remote Desktop (RDP) to the Windows server.**

#### Step-by-step Instructions

1. From the [AWS Management Console](https://console.aws.amazon.com), select **Services -> EC2**, or **Search** for **EC2**.
![Step 1](/images/020_self_guided_setup/search-ec2.png)

1. Select **AMIs**.
![Step 2](/images/020_self_guided_setup/Ec2_AMI.png)

1. Change to **Public images**.
![Step 3](/images/020_self_guided_setup/ami_public.png)

1. Add filter **"UFT"** and press Enter.
![Step 3](/images/020_self_guided_setup/uft_ami_details.png)

1. Select the **UFT 15_02 update...**, open **Actions** and select **Launch**.
![Step 3](/images/020_self_guided_setup/ami_launch.png)

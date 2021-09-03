---
title: "4. Launch EC2 Instance"
chapter: false
weight: 32
---

## Launch EC2 Instance

1. It is recommended to select the **m4.xlarge** instance type.
![Step 1](/images/020_self_guided_setup/choose_instance.png)
Click **Next: Configure Instance Details**.

1. Configure the instance details based on your account's requirements.
![Step 2](/images/020_self_guided_setup/instance_details.png)
Click **Next: Add Storage**.

1. It is recommended to have at least 80 GB free in the Root **Volume Type**.
![Step 3](/images/020_self_guided_setup/add_storage.png)
Click **Next: Add Tags**.

1. It is recommended to add personal tags in order to easily identify this instance. For example:
![Step 4](/images/020_self_guided_setup/tags.png)
Click **Next: Configure Security Group**.

1. It is recommended that you configure the security group with your IP. If you want to open the server for global access, keep the **Source** as 0.0.0.0/0
![Step 5](/images/020_self_guided_setup/security_group2.png)
Click **Next: Review and Launch**.

1. Review the details and click **Launch**.

1. If you have an existing key-value pair, select it. If not, create a new one, and click **Download Key Pair**.
![Step 6](/images/020_self_guided_setup/create_key_pair.png)

1. Click **Launch Instances**.


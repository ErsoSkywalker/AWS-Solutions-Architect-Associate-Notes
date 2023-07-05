# What is EC2? (Amazon Elastic Compute Cloud)

The virtual machine service from AWS, focused on provide compute force for different situations.

- Scalable up or down to handle changing situations.
- Uses virtual machines instances.
- You can use [Amazon Machine Images (AMIs)](AMIs.md), those are like snapshots created by AWS, the comunity or you/your organization.
- There are multiple instance types for different cases, you can configure CPU, Memory, Storage and Networking capacity as you need.

You can place your EC2 instances in different Regions and Availability Zones.

EC2 Instances have storage volumes for temporary data, if you stop, hibernate or terminate your instances, the data will be deleted.
You can attach Persistence storage volumes for your data using [Amazon Elastic Block Store](EBS.md).

## Instance Types

There are a lot of EC2 instance types to create your instance.
[You can check the updated list of instance types here.](https://aws.amazon.com/es/ec2/instance-types/)

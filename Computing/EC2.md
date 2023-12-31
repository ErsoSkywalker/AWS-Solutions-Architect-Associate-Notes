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

There are a lot of EC2 instance types to create your instance. You can select the best option for your instance considerating Memory, CPU, Storage and Networking.
[You can check the updated list of instance types here.](https://aws.amazon.com/es/ec2/instance-types/)

The name of instance types is defined by this rules:

### FOR EXAMPLE: _C5n.xlarge_ Where:

- First Letter (C) is reference for family, which in this case represents compute optimized intances.
- The second (5) is referencing the generation of the family.
- Third one (n) makes reference to the network behaviour.
- Last part (xlarge) is the size of the instance, which represents different combinations of resources like CPU or Memory.

## Purchasing Options

There are multiple options for purchasing EC2 instances, that allows you to optimize costs.

- **On-Demand Instances**: Default EC2 purchasing option. You pay hourly and you are not commited to a long-term use.
- **Reserved Instances**: Allows users to reserve **for one or three years**, this is kinda cheap but you have to pay upfront. You can save up to 75% compared to On-Demand Instances.
  There are two subtypes of Reserved Instances:
  - All Upfront: You are paying for the entire reservation upfront, so that will reduce your long time cost.
  - Partial Upfront: You pay a part, but theres a part you need to cover also.
  - No Upfront: You don't pay Upfront, but you have the commitment of use the reserved EC2 instance.
- **Spot Instances**: So you take instances at very low cost, but your instances can be terminated by AWS and taken for someone else, so if you use them, you have to think in processes that can be finished and continued in different times.

## Saving Plans

You can use different Saving plans focused to get discounts on using compute options like AWS EC2, AWS Fargate and AWS Lambda. This Saving Plans are also for **1 or 3 years**.

Use AWS Cost explorer to check which saving plans are aplicable for you.

There are two different types:

- **Compute Saving Plans**: This plan required to commit to a specific ammount of compute resources for **one or three year term**, you can use EC2, Lambda, Fargate to fulfill it.
- **EC2 Instances Saving Plans**: Requires to commit to a specific family and size for a **one or three year term**, you can change the size within the same family during the term.
- **SageMaker Saving Plans**: TBD

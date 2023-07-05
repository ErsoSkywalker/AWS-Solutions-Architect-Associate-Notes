# What are AMIs? (Amazon Machine Image)

- Provides the information required to launch an instance.
- You can Launch multple instances using the same AMI.

Just imagine you are setting a computing lab for a high school, so you'll set Windows 8 (bc you hate all the students lol) to all the computers, but also you have to install Office Word, Excel and Halo Custom Edition, also you have to set Firewall rules. What would you do? Install Windows 8, configure the firewall and then download and install all the stuff in all the computers? Or just create an image with all the stuff ready and configured, and then install it in all the computers?

So you create the image with all the stuff installed and then install the image in all the computers. It's the same here, you can create an EC2 instance, install Docker Runtime, install Git, create a .txt file and then create an Image of that, so every time you create a new instance, you can use the AMI to have cloned instances.

What does AMIs include?

- One or more [EBS](EBS.md) snapshots
- Launch permissions to control which AWS accounts can use it.
- Block devide mapping to specify which volumes can be attached to the EC2 instance when it is launched.

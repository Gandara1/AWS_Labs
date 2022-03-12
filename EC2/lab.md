# EC2 Lab1
---
---
>***Open the AWS console at [aws.amazon.con](https://aws.amazon.com/)***
>
>Select EC2 from the search bar after you log in. 
>
>![Ec2 Navigation](/EC2/images/ec2_search.png)
>
>You should be taken tot eh EC2 dashboard pictured below
>![EC2 Dash board](/EC2/images/ec2_dashboard.png)
>Click Launch instance and select the launch instance option
>
>**Step 1:** Choose your Amazon Machine Image
> 
>>***You can choose from the quick start guide, your own custom images, marketplace images, or community created images.***  
>
>For purposes of this lab, choose a free tier image.  I will select an ubuntu image shown below. 
> ![AMI GIF](images/select_AMI/select_AMI.gif)
> **Step 2:** Choose the instance type - t2.micro
> 
> **Step 3:** Configure instance details. For purposes of this lab we will keep all of these settings as default. 
> 
> **Step 4:** keep default storage options
> 
> **Step 5:** You can add tags to the VM
> ![Tags](images/tags.png)
>**Step 6:** Add security group with ports 22 and 80 open.  
> ![NSG](images/NSG.png)
>>***click review and launch at the bottom right of your screen***
>>
>>***Ensure all of the settings are as expected then click launch.***
>>
>>***Once you click launch you will be prompted for an SSH key*** 
>>
>>***You can either create and download a new key or use an existing key.*** 
![create_instance](images/launch_instance/launch_instance.gif)



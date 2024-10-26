# AZURE--TASK-3


Step-1

Create multiple VMs (i.e.) VM1 and VM2 in two different Virtual networks.

**  To create multiple VMs (VM1 and VM2) in two different Virtual networks in Azure, you can follow these steps:

1) Log in to the Azure portal (https://portal.azure.com/)

2) Click on the "Create a resource" button and select "Windows Server" or "Linux" as the operating system for the VMs.

3) Fill out the basic settings for the VM, such as the name, size, and username/password.

4) In the "Advanced" tab, you can select the virtual network and subnet that the VM will be created in.

5) Repeat steps 2-4 to create the second VM (VM2) and make sure to select a different virtual network for it.


 Step-2

 **Create a Network Security Group to establish connection among VMs to ping each other and understand how the priority works

 1) Log in to the Azure portal https://portal.azure.com

2) Go to the "Network security groups" page and click on the "Add" button to create a new NSG.

3) Fill out the basic information for the NSG, such as the name and resource group.

4) Click on the "Inbound security rules" tab and create a new rule.

5) In the new rule, set the "Source" to "Virtual network" and select the virtual network that your VMs are in.

6) Set the "Destination" to "Virtual network" and select the same virtual network.

7) Set the "Protocol" to "ICMP" and the "Source port ranges" and "Destination port ranges" to "*"

8) In the "Priority" field, you can assign a priority number to this rule (e.g. "100"). Higher priority rules are evaluated before lower priority rules.

9) Repeat step 4-8 for the outbound security rule

10) Once the NSG is created, you should be able to ping between VMs in the same virtual network.




 DAY -3 TASK is Finshed!!!......

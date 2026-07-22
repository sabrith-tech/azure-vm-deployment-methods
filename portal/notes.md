# GUI Deployment

## What I ran / clicked
- Created a Resource Group: my-first-vm
- Selected subscription: Azure for students
- Clicked at Virtual machines from create resources and gave it name "my-first-vm" 
- Selected region as "Central India"
- Operating system: Linux (Ubuntu 24.04) and the Image size selcted to B2 series for cost management.
- Enabled Auto Shutdown after 2 hours for cost management.
- Reviewed and deployed.
- Checked the status of the Virtual Machine, used system terminal to connect to the VM.


## Configuration
- VM name: my-first-vm
- Image: Ubuntu 24.04 LTS
- Size: Standard_B2ats v2
- Region: Central India
- Auth method: SSH key 
- Resources created: VM, NIC, Public IP, NSG, OS Disk 

## Result
- Deployed in: 3 minutes
- Verified running: ![alt text](<vm portal running-1.png>)
- Resource group deleted

## When to use this method
GUI is good for learning and ad-hoc work, but it is not repeatable, not version controlled and cannot be code reviewed which is why production environment move to IaC(Infrastructure as Code)

## What I learned
- Creating resources using portal is useful for beginners who try to explore the environment,
- Creating Multiple resources simultaneously can be challenging by using the GUI.
- Using GUI to create resources can be useful for simple tasks and self-projects.
## <h1 style="text-align: center;">Implementing Auto Scaling Group </h1>
---

Here is the Visual Presentation of how Auto-Scaling Group Works
<img src="../../../assets/ASG/Example Architectural Diagram.png"  width="1000" height="500"/> <br><br>
---


First we need to create a Auto-Scaling Group, We can see the tab at the bottom of the left side in our EC2 GUI
<img src="../../../assets/ASG/1.png"  width="1000" height="500"/> <br><br>
---


In this Tab, we need to create a Launch Template.

An AWS Launch Template is a resource in Amazon EC2 that helps you define and store configuration details required to launch an instance. It’s like a blueprint for launching EC2 instances in a consistent and repeatable way.
<img src="../../../assets/ASG/2.png"  width="1000" height="500"/> <br><br>
---

Configuring my launch template
<img src="../../../assets/ASG/3.png"  width="1000" height="500"/> <br><br>
<img src="../../../assets/ASG/4.png"  width="1000" height="500"/> <br><br>


Adding some basic Script to install a web server for visualization
<img src="../../../assets/ASG/5.png"  width="1000" height="500"/> <br><br> 
---


Summary of Launch Template
<img src="../../../assets/ASG/6.png"  width="1000" height="500"/> <br><br>
---


Configuring Instance launch options
<img src="../../../assets/ASG/7.png"  width="1000" height="500"/> <br><br>
---


In this section we can integrate our Auto-Scaling Group with other AWS services like Load balancer, ARC, Health Checks
<img src="../../../assets/ASG/8.png"  width="1000" height="500"/> <br><br> <img>
---


In this section we will configure the group size and scaling of our Auto-Scaling Group
<img src="../../../assets/ASG/9.png"  width="1000" height="500"/> <br><br>
<img src="../../../assets/ASG/10.png"  width="1000" height="500"/> <br><br>
---

We can also add notification but I will not add it because it is optional
<img src="../../../assets/ASG/11.png"  width="1000" height="500"/> <br><br>
---
Summary of our Auto-Scaling Group configuration
<img src="../../../assets/ASG/12.png"  width="1000" height="500"/> <br><br>
<img src="../../../assets/ASG/14.png"  width="1000" height="500"/> <br><br>
<img src="../../../assets/ASG/15.png"  width="1000" height="500"/> <br><br>
---
Here is the overview of our newly created ASG
<img src="../../../assets/ASG/16.png"  width="1000" height="500"/> <br><br>
---
If we go to the activity tab, we can see that the Auto-Scaling Group automatically creates an instance because of our previous configuration that the minimum size of our Auto-Scaling Group is 1

0 ---> 1
<img src="../../../assets/ASG/17.png"  width="1000" height="500"/> <br><br>
<img src="../../../assets/ASG/9.png"  width="1000" height="500"/> <br><br>
---

If we look in to our Instance Tab, we can already see that the created instance is running
<img src="../../../assets/ASG/18.png"  width="1000" height="1000"/> <br><br>

## <h1 style="text-align: center;">Example Architectural Diagram </h1>
<img src="../../../assets/ALB/Example Architectural Diagram.png"  width="1000" height="500"/> <br><br>

---
First we need to create 2 instances that we want to implent Application Load Balancer
<img src="../../../assets/ALB/Creating Instance.png " width="1000" height="500"/> <br><br>
---
I added some basic Scripts to create a webserver and an 'echo' to identify what IP address of the instance are using
<img src="../../../assets/ALB/Creating Instance 2.png " width="1000" height="500"/> <br><br>
--- 
Checking the web server of both instances
<img src="../../../assets/ALB/Web Server.png" width="1000" height="500"/> <br><br> 
---
Next is to Create an Load Balancer
<img src="../../../assets/ALB/Create ALB.png" width="1000" height="500"/> <br><br> 
---
Configuring the load balancer
<img src="../../../assets/ALB/Create load balancer.png" width="1000" height="500"/> <br><br>
---
Configuring the Network Mapping, Selecting which AZ are we going to select. `Note: select at least 2 AZ`
<img src="../../../assets/ALB/Network Mapping.png" width="1000" height="500"/> <br><br>
---
Next is we need to create another Security group `make sure to only allow port HTTP port 80 to the inbound rules or else The ALB will not receive any traffic`
<img src="../../../assets/ALB/Create another SG.png" width="1000" height="500"/> <br><br>
---
After that, we need to create a target group `a target group is a logical group of instances that a load balancer can send traffic to`
<img src="../../../assets/ALB/Target Group.png" width="1000" height="500"/> <br><br>
---
Select the instances that you want to group and to load balance
<img src="../../../assets/ALB/Target Group 2.png" width="1000" height="500"/> <br><br>
---
here is the summary of the target group
<img src="../../../assets/ALB/Target Group 3.png" width="1000" height="500"/> <br><br>
---
here is the finish product
<img src="../../../assets/ALB/Finish.png" width="1000" height="500"/> <br><br>
---
to check if the load balancer is working, the web server should have 2 IP Addresses Balancing
<img src="../../../assets/ALB/working.png" width="1000" height="500"/> <br><br>

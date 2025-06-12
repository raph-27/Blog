## <h1 style="text-align: center;"><Strong>Create IAM User </h1>

---
First we need to go services and search IAMFirst we need to go services and search IAM
<div style="text-align: center;">
<img src="../../../assets/IAM/1.png"> <br><br></img></div>
---


Here we can see the list of IAM user <br>
<div style="text-align: center;">
<img src="../../../assets/IAM/2.png"/> <br><br></img></div>
---


Click create user and edit your preferences for the new IAM user<br>
<div style="text-align: center;">
<img src="../../../assets/IAM/3.png"  width="1000"/> <br><br></img></div>
---


you can choose what to do the IAM user `add user to group` ,  `copy permission` or `attach policies directly` <br></img>
<div style="text-align: center;">
<img src="../../../assets/IAM/4.png"  width="1000"/> <br><br></img>
<img src="../../../assets/IAM/5.png"  width="1000"/> <br><br></img> </div>
---


review your configuration and make sure to download the `.csv file` and email to the user <br></img>
<div style="text-align: center;">
<img src="../../../assets/IAM/6.png"  width="1000"/> <br><br></img></div>
---


Check the User Group `admin` and see if user `test` is there <br></img>
<div style="text-align: center;">
<img src="../../../assets/IAM/9.png"  width="500"/> <br><br></img> </div>
---


## <h1 style="text-align: center;"> Create Access key for Programmically Use<br></h1>
<div style="text-align: center;">
<img style src="../../../assets/IAM/10.png"  width="1000"/> <br><br></img> </div>
---


Retrieve access keys for use and make sure to save it, because if we forgot either of the 2 we can't reset it and we need to replace it<br>
<img style src="../../../assets/IAM/11.png"  width="1000"/> <br><br></img>
---

Check the CLI in our machine and check if the IAM User can access the AWS CLI
<img style src="../../../assets/IAM/12.png"  width="1000"/> <br><br></img>
---

## <h1 style="text-align: center;">Delete IAM User </h1>
---

Go to the IAM User Console GUI and Click delete
<div style="text-align: center;">
<img style src="../../../assets/IAM/13.png"  width="1000"/> <br><br></img> </div>
---

Check the IAM Users if the User `test` is deleted
<div style="text-align: center;">
<img style src="../../../assets/IAM/14.png"  width="1000"/> <br><br></img> </div>
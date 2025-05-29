First We need to get Access Key and the Private key of our AWS Account
<img src="../../../assets/BLOGS IMAGES/Creating Instances Using Terraform/aws configure.png"  width="800"/> <br><br>
Next is need to create a directory for the config file of terraform <br>
<img src="../../../assets/BLOGS IMAGES/Creating Instances Using Terraform/create folder.png"  width="500"/> <br><br>
after that, we need create a config file and then editing it base on our preferences <br>
<img src="../../../assets/BLOGS IMAGES/Creating Instances Using Terraform/Editing maintf.png"  width="500"/> <br><br>
we need to impement `terraform init` in our directory <br>
<img src="../../../assets/BLOGS IMAGES/Creating Instances Using Terraform/init.png"  width="800"/> <br><br>
after all of that if we want to, we can check the syntax and internal consistency of your configuration files using `Terraform Validate`. <br>
<img src="../../../assets/BLOGS IMAGES/Creating Instances Using Terraform/validate.png"  width="1000"/> <br><br>
after we make sure that our configuration are valid, we can use `terraform apply` to begin the creation of our instance <br>
<img src="../../../assets/BLOGS IMAGES/Creating Instances Using Terraform/apply.png"  width="1000"/> <br><br>
we can go to our AWS Console to check if the instance is created<br>
<img src="../../../assets/BLOGS IMAGES/Creating Instances Using Terraform/Finish Product.png"  width="1200"/> <br><br>
we can also delete the instance using terraform by using `Terraform Destroy`<br>
<img src="../../../assets/BLOGS IMAGES/Creating Instances Using Terraform/destory 1.png"  width="1200"/> 
<img src="../../../assets/BLOGS IMAGES/Creating Instances Using Terraform/destory 2.png"  width="1200"/> <br><br>
as we can see, the instance is terminated
<img src="../../../assets/BLOGS IMAGES/Creating Instances Using Terraform/Terminated.png"  width="1200"/> <br><br>



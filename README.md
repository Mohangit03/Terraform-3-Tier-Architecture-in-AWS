# Terraform-3-Tier-Architecture-in-AWS
Terraform 3-Tier Architecture in AWS


# AWS CONFIGURE
•	Go to the AWS Management
 Go to the IAM
 Create the IAM Account with Access Key and Secret Key 
 Download the .csv File.
•	Open the CMD Prompt 
 Enter the #aws configure Command
 Configuration the Access Key and Secret Key.
 
•	Create the .html file
•	Put the Name to .sh format, this is used for User Data.
Configure the Provider
•	Open the Visual Studio Code.
•	Create on Directory  Inside the Directory upload the .sh file.
•	Create the Main.tf file and upload the following codes in the Main.tf file.
•	Put the Code for Configure the Provider  Specify the Region.
 

# Create the Networking Parts
   •	Create a VPC by using the Terraform Codes, so Upload the codes in the Main.tf file
   •	Following the VPC Codes upload the Subnet and Internet Gateway Codes.
 
 
 
 
 
 

# Creating the Web Server
 •	Launch the two web servers in different availability zone by using the terraform code.
 •	These codes are uploaded for the Main.tf file under the Networking Codes.
 
 
 
 
 
 

# Creating the Database
•	Creating the Database by using Terraform Codes.
•	Upload these codes in the Main.tf file.
 
 

•	Now, all the infrastructure is uploaded to the Main.tf and saved.
 # Then following commands are used to deploy the Codes.
 1 terraform init
 2 terraform fmt
 3 terraform validate
 4 terraform plan
 5 terraform apply
 
 
 
 

•	Now Codes are deployed successfully.
 
 
 
 
 
 
 
 

 

# Provisioning-of-Jenkins-Server-via-Terraform-
Provisioning of Jenkins Server via Terraform 
Download Terraform binary in your laptop, extract it & copy the path of the Terraform application and set that path in the Envirinment Varibles
Open Visual Studio code & open the folder of Wrokspace_1.
cd .\setups\
Apply below commands:
terraform version
terraform init
terraform validate
terraform plan
terraform apply --auto-approve
Note: After your infrastructure is created destroy the infra using the below command
terraform destroy --auto-approve

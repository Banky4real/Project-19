## **Documentation for Project 19**
## **Automating our Infrastructure with terraform using terraform cloud**

### Creating terraform cloud account and organization

![terraform-cloud-account](./Images/terraform-cloud-account.png)

### Configuring our Workspace on Terraform Cloud, so we need to configure access to our version control system which is Gitlab on Terraform Cloud using the credentials provided by terraform cloud.

### Configuring Version control system on terraform cloud

![Configuring-Version-control-system-on-terraform-cloud](./Images/Configuring-Version-control-system-on-terraform-cloud.png)

### Using the Open Authentication application on gitlab, we integrate gitlab with Terraform cloud using the credentials provided by terraform cloud and gitlab

![integrating-gitlab-with-terraform-cloud](./Images/integrating-gitlab-with-terraform-cloud.png)

![credentials-for-terraform-cloud](./Images/credentials-for-terraform-cloud.png)

### Workspace created

![workspace-created-successfully](./Images/workspace-created-successfully.png)

### Configuring Workspace Environmental variables

![workspace-environmental-variable](./Images/workspace-environmental-variable.png)

### Packer Installation

![packer-installed](./Images/packer-installed.png)

### Amazon Plugin for packer Installed

![packer-amazon-plugin-installed](./Images/packer-amazon-plugin-installed.png)

### Packer Build run for Bastion, error encountered and AMI Changed to an available one

![packer-build-run-for-bastion](./Images/packer-build-run-for-bastion.png)

### AMI Changed to an available one and bastion ami built successfully with packer

![bastion-AMI-successfully-built-with-packer](./Images/bastion-AMI-successfully-built-with-packer.png)

### AMI available on Console and Instance terminated

![AMI-available-on-console](./Images/ami-created.png)

![instance-terminated](./Images/instance-terminated.png)

### Packer Build run for Nginx

![packer-build-run-for-nginx](./Images/packer-build-run-for-nginx.png)

### Nginx AMI available on Console

![nginx-ami-available-on-console](./Images/nginx-ami-available-on-console.png)

### Packer Build run for Ubuntu

![packer-build-run-for-ubuntu](./Images/packer-build-run-for-ubuntu.png)

### Ubuntu AMI available on Console

![Ubuntu-ami-available-on-console](./Images/Ubuntu-ami-available-on-console.png)

### Packer Build run for Web AMI

![packer-build-run-for-web](./Images/packer-build-run-for-web.png)

### WEB AMI available on Console

![web-ami-available-on-console](./Images/web-ami-available-on-console.png)

### Changes pushed to Gitlab

![changes-pushed-to-gitlab](./Images/changes-pushed-to-gitlab.png)

### Changes available on Gitlab

![changes-available-on-gitlab](./Images/changes-available-on-gitlab.png)

### Terraform Cloud Triggered New Plan

![new-plan-triggered-on-terraform-cloud](./Images/new-plan-triggered-on-terraform-cloud.png)

### Terraform Plan Applied successfully after fixing some errors

![terraform-apply-successful](./Images/terraform-apply-successful.png)

### Target group fails health check

![target-group-failed-health-check](./Images/target-group-failed-health-check.png)

### Listeners Deregistered from Target group and Load Balancers

![listeners-deregistered-from-LBs](./Images/listeners-deregistered-from-LBs.png)

### Cloning down our ansible repo on our bastion server so that we will be able to connect to our aws account and dynamically pull down the ip addresses of our instances so as to be able to deploy on them

![cloning-our-ansible-deploy-repo-on-bastion](./Images/cloning-our-ansible-deploy-repo-on-bastion.png)

### Ansible can now dynamically pull down our inventory from our aws account

![ansible-dynamic-inventory](./Images/ansible-dynamic-inventory.png)

### Adding our listeners back to our load Balancer

![terraform-cloud-ready-to-deploy-our-added-resources](./Images/terraform-cloud-ready-to-deploy-our-added-resources.png)

### Running our playbook to deploy our wordpress and tooling application

![playbook-ran-successfully](./Images/playbook-ran-successfully.png)

### Checking the status of our wordpress website to be sure its working locally before accessing it on the Web
![Word-press-website-working-locally](./Images/Word-press-website-working-locally.png)

### Nginx Target group, tooling and wordpress target group turns Healthy after updating our playbook with our EFS access point and RDS Endpoint

![nginx-target-group-healthy](./Images/nginx-target-group-healthy.png)

[tooling-target-group-healthy](./Images/tooling-target-group-healthy.png)

[wordpress-target-group-healthy](./Images/wordpress-target-group-healthy.png)

### Tooling Website Live

![tooling-website-live](./Images/tooling-website-live.png)

### WordPress Website Live

![wordpress-website-live](./Images/wordpress-website-live.png)
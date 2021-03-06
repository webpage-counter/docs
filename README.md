# This is the documentation for the Webpage counter app in production

## Detailed READMEs with explanation can be found in each of the repos

AMI used for the project - ami-0ae16567e95c768a1


### TO DO:

- [ ] Add prometheus to consul, nomad and vault
- [ ] Deploy my own PTFE


### DONE:

- [x] Create a repo and ami for packer-aws-bionic box that is going to be used for this project
- [x] Create a repo `terraform-aws-network` where will be the code for the network module
- [x] Create a module inside TF Cloud for the networking part
- [x] Create a repo `ops-aws-network` and deploy the network module with TF Cloud
- [x] Create a repo `terraform-aws-consul` where will be the code for the consul module
- [x] Create a module inside TF Cloud for the consul part
- [x] Create a repo `ops-aws-consul` and deploy the consul module with TF Cloud
- [x] Create a repo `terraform-aws-nomad` where will be the code for the nomad module
- [x] Create a module inside TF Cloud for the nomad part
- [x] Create a repo `ops-aws-nomad` and deploy the nomad module with TF Cloud
- [x] Create a repo `terraform-aws-vault` where will be the code for the vault module
- [x] Create a module inside TF Cloud for the vault part
- [x] Create a repo `ops-aws-vault` and deploy the vault module with TF Cloud
- [x] Create a repo `docker-python-pagecounter` that is going to package every new version of the app inside a container
- [x] Create a repo `terraform-python-pagecounter` that is going to create a load balancer and start the nomad jobs and run the app
- [x] Merge DEV and Travis part of the app
- [x] Make nomad UI/API public
- [x] Run nomad job using terraform-nomad provider
- [x] Test a new release of the application with no downtime

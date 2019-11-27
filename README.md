# This is the documentation for the Webpage counter app in production

## Detailed READMEs with explanation can be found in each of the repos

AMI used for the project - ami-0230ee9fd9ee23718


### TO DO:

- [ ] Create a repo `terraform-aws-vault` where will be the code for the vault module
- [ ] Create a module inside TF Cloud for the vault part
- [ ] Create a repo `ops-aws-vault` and deploy the vault module with TF Cloud
- [ ] Create a repo `docker-python-pagecounter` that is going to package every new version of the app inside a container
- [ ] Create a repo `terraform-python-pagecounter` that is going to create a load balancer and start the nomad jobs and run the app


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
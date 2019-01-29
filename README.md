### this repository is to do some automation to create your environment automatically 
first install terraform and git client on your machine 
  - apt-get install terraform
  - apt-get install git 
second clone this repository 
  - git clone https://github.com/MohamedOthman/devops.git
third provision the machine from terraform file mentioned in the repository 
  - terraform init 
  - terraform plan 
  - terraform apply 
fourth install ansible in the machine 
  - apt-get update && apt-get install ansible 
finally install docker with ansible 
  - ansible-playbook 

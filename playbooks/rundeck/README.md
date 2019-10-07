# Playbook to set up a server running Rundeck in an AWS env
# The following variables need to be set
--- 
# tasks/configure_rundeck.yml
admin password should be entered as an md5 hash

# tasks/create_tron_user.yml
set an ssh key used by a user named "tron" to ssh into servers

# rundeck.json
source_ami - set the ami you use as a base
ami_users - a list containing appropriet ami users by id
vpc_id - the id of your AWS VPC
subnet_id - the id of what AWS subnet you want to use
security_group_ids - security groups to attach

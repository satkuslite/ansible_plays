# ansible_task

Usage Instructions
1. Ensure that Ansible is installed on the control node where you plan to execute the playbook.

2. Create YAML file, cred.yml for your AWS credentials and modify vars.yml for your global needs, for the infrastructure setup.

3. Customize the roles according to your specific requirements. You may need to modify variables, tasks to match your desired configuration.

4. Execute the playbook using the following command:

ansible-playbook execute.yml --ask-vault-pass

5. Sit back and relax while Ansible automates the deployment of your web application AWS infrastructure, apache server and WordPress.

6. Finish setting up at http://(public_ip)/wordpress

*****

execute.yml

This play sets up the necessary infrastructure components such as the security group, EC2 instances, and RDS database.

Then deploys WordPress on the EC2 instances.

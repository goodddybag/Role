# ansible_study
Learning ansible and playbooks

1)Create two machines. Ubuntu and centOS 

Create a new user. Give the user sudo permissions

Write an Ansible playbook to update and upgrade the server depending on the os

Install apache on both Ubuntu and centOS using 1 task.

Also write a task to make sure apache is started

Copy a default html page from the Ansible command line and deploy it on both servers.

Everything must be ran with the user you created.

NOTE: when done with this task write a detailed blog on the steps you took 



2) create a 3 ubuntu machines and 1 centos machine and in your inventory section create a group and call it “webserver”.

Create another group and call it centos

All the ubuntu machines should be under the webserver group 

And the centos machine should be under the group named centos

Write a playbook to install apache on the centos machine using the group

Also write a task to make sure apache is started

In the same playbook write a task that installs nginx on the ubuntu group

Also write a task to make sure nginx is started

Lastely create a parent group in the inventory file and put both the webservers and centos group under it.

Write anothe task that helps to update the ubuntu server and centos server using the group you created. And also installs php and run it as a pre task


NOTE: when done with this task write a detailed blog on the steps you took 





3)ROLES:

- Write a role to install apache. And anothe role to copy a default html page to the default apache webpage.

And also write a handler that helps you restart apache.

- write a role to install terraform

- write a role to install docker and run an ubuntu container with it. Using ansible.

- write a role to install jenkins and open port 8080 with firewall.

NOTE: when done with this task write a detailed blog on the steps you took 



4) create 4 users (james, amaka, joy and cloudtopg) using a loop in ansible

NOTE: when done with this task write a detailed blog on the steps you took 


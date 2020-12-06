# Hadoop_configuration_Ansible

I've created two Ansible Playbooks for Configuring both NameNode & DataNode in a Hadoop cluster.\

Ansible is a great tool for Configuration Management & Automation. This Task was given by Sir Vimal Daga in the Arth training recently.

## ARTH Task-11.1
🔰 Write an Ansible PlayBook that does the following operations in the managed nodes:\
🔹 Configures NameNode\
🔹 & one to Configure DataNode\
Therefore, you can configure whole Hadoop Cluster using these codes using just 2 commands. Here, I have created two Host Groups named: namenode & datanode. So, to configure multiple OS as DataNode, just add there IP's under datanode Host group, similarly for NameNode as well. 

###### NOTE:
- Required Softwares: jdk & Apache Hadoop
- To complete requirements for configuring Hadoop cluster, you need to get above softwares in this directory: "requirements/softwares/"
- For this, just execute the Ansible Playbook named "complete_requirements.yml" firstly before starting any Configuration.

Hope you guys liked it and learned something new. Thankyou, I'll meet you in the next one. 😊

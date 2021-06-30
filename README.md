# Hadoop configuration using Ansible

I've created two Ansible Playbooks for Configuring both NameNode & DataNode in a Hadoop cluster.

Ansible is a great tool for Configuration Management & Automation. This Task was given by Sir Vimal Daga in the Arth training recently.

## Detailed Description
🔰 Write an Ansible PlayBook that does the following operations in the managed nodes:\
🔹 Configures NameNode\
🔹 & one to Configure DataNode\
Therefore, you can configure whole Hadoop Cluster using these codes using just 2 commands. Here, I have created two Host Groups named: namenode & datanode. So, to configure multiple OS as DataNode, just add there IP's under datanode Host group, similarly for NameNode as well. 

- I've demonstrated how to use this code & discussed some other details in this video which I posted on Linkedin. You can watch this to know more:
https://www.linkedin.com/posts/samarpratapsingh_vimaldaga-righteducation-educationredefine-activity-6747203371968577536-W-Y0

###### NOTE:
- Required Softwares: jdk & Apache Hadoop
- To complete requirements for configuring Hadoop cluster, you need to get above softwares in this directory: "requirements/softwares/"
- For this, just execute the Ansible Playbook named "complete_requirements.yml" firstly before starting any Configuration.

Hope you guys liked it and learned something new. Thankyou, I'll meet you in the next one. 😊

# final-project

Project Description :
Infrastructure Setup :
vm_0: for running Prometheus Server vm_1 : for running Mysql Server vm_2: for running Grafana Server
Task 0 : Install MySQLD_Exporter, & NodeExporter on vm_1
Task 1: Install AlertManager on vm_0
Task 3: Configure Alert Manager to Send Email Notifications.
Task 4: Write a Python Script in vm_1 and Produce the Following Output :
Press 1 - Perform CPU Stress Test
Press 2 - Perform Memory Stress Test Press 3 - Perform Disk Stress Test
Press 4 - Perform SQL Stress Test ( same as task shared Yesterday)
Task 5: Write Rules in Prometheus Node to Monitor CPU/Memory/Disk/SQL Stress Test.
- if the Resource Usage Exceeds 70%, alert Manager should be able to trigger an Email Notification
- Configure alertManager to Send CC to me at professional01@gmail.com
Task 6: Configure Grafana Server with NodeExporter & MySQL Dashboard to Monitor the resource when
Performing Stress Test.
Task 7: Create a GitHub Repo containing All Project files including py files, yaml files etc.
Create a ReadMe File containing Project Description, Objectives and Details.

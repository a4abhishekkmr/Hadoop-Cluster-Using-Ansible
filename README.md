## Hadoop CLuster Using Ansible ##

Configured Hadoop and start cluster services using Ansible Playbook.

ALl the services of HAdoop Cluster and cluster formation is done by Ansiblle 
very easily. just running by a file called sw11.yml by
ansible-playbook -v sw11.yml

Which will connect it to target node then do tasks like
Installing java and hadoop
then copying hdfs-site and core-site 
etc. and starting NAmenode and DATA node sevices by command of 
HAdoop daemon.sh start namenode
hadoop daemon.sh start datanode

and then the services of HAdoop cluster is forking fine
yu can check manually by checking the report in browser view or directly in any name/
datanode




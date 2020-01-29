# yufei_ansible


hadoop operations:
ansible-playbook -i hosts.yml main.yml  -u zhaoyufei -t hadoop  --limit hadoop_slave --list-tags  
将显示所有的可支持的hadoop相关操作，    
比如：hadoop, hadoop_config, hadoop_restart_datanode, hadoop_restart_namenode, hadoop_restart_nodemanager, hadoop_restart_resourcemanager, hadoop_setup    
执行某项操作：  
ansible-playbook -i hosts.yml main.yml  -u zhaoyufei -t hadoop_config  --limit hadoop_slave



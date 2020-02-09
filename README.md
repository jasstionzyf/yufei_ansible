# Document

ansible based on functions to admin big data and ai stack

support frameworks:
- [x] hadoop
- [x] kafka
- [x] zk
- [x] redis (https://github.com/geerlingguy/ansible-role-redis)



### hadoop
```
ANSIBLE_ENABLE_TASK_DEBUGGER=True ansible-playbook -i hosts.yml main.yml  -u zhaoyufei -t hadoop_restart_datanode --limit hadoop_slave
support tags: hadoop_config, hadoop_restart_datanode, hadoop_restart_namenode, hadoop_restart_nodemanager, hadoop_restart_resourcemanager, hadoop_setup

```

       




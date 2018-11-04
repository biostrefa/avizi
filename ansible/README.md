After installing ansible,
edit /etc/ansible/hosts and include 

```
[webservers]
142.93.221.134 ansible_python_interpreter=/usr/bin/python3

[dbservers]
142.93.221.134 ansible_python_interpreter=/usr/bin/python3
```


at the end. Ansible will deploy on all those servers.
Also, the development file's ip has to be updated as well.

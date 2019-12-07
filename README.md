# Start | Stop | Restart Tasks in Ansible

* ## Requirements:
Install Ansible using following command:
```bash
$ dnf update
$ dnf install ansible
```

* ## Usage:
```bash
$ sudo ansible-playbook task.yml
```
* ## Description:
The following code initially starts the apache web server on local machine, checks status and
stops it.Then it again checks the status and restarts the apache web-server and finally exits 
after checking the status for the last time.

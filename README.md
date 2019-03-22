# ansible  
使用方法：  
1） 部署  
ansible-playbook /etc/ansible/roles/webServers1/webServers1.yml -t deploy -v --vault-password-file /etc/ansible/ansible.vpf
2)  重启  
ansible-playbook /etc/ansible/roles/webServers1/webServers1.yml -t restart -v --vault-password-file /etc/ansible/ansible.vpf
3)  回滚  
ansible-playbook /etc/ansible/roles/webServers1/webServers1.yml -t rollback -v --vault-password-file /etc/ansible/ansible.vpf

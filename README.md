Reusable setup of development cloud instances via Ansible

cat /etc/ansible/hosts
[dev_instances]
dev_xenial

Set the local vars or dev_instances_vars.yml with username, git_user_name and git_user_emal

```
username: yourusername
git_user_name: gitusername
git_user_email: gituseremail@example.com
launchpad_username: lp.user.name
```

$ ansible-playbook dev_instances.yml

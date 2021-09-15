# ISUCON Ansible

## Execute default roles

```bash
$ ansible-playbook -i hosts site.yml
```

## Execute a specific role

```bash
$ ansible contestant-ubuntu-servers -i hosts -m include_role -a name=<role_name>
```

## Other

`roles/netdata` is copied from [https://github.com/netdata/community/tree/main/netdata-agent-deployment/ansible-quickstart](https://github.com/netdata/community/tree/main/netdata-agent-deployment/ansible-quickstart)
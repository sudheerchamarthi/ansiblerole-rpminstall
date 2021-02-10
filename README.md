# Prerequisites

- Copy the latest package to roles/rpm/files/
- Update the variables in group_vars/all.yml

Run the ansible playbook

## Command to run Playbook

```bash
ansible-playbook -i hosts -u <username> --private-key=<path/to/key>  main.yml
```

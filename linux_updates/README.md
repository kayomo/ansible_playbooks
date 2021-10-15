# Update scripts for Linux

Updates all installed packages on all machines in hosts file to latest version (Debian & Ubuntu).

**Usage:**

Updates all machines:
```
ansible-playbook update_linux_machines.yaml
```

Updates all machines in section "pi":
```
ansible-playbook -l pi update_linux_machines.yaml
```

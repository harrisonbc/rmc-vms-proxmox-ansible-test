Ansible Playbook to deploy 4 nodes on Proxmox

Edit Variables in the playbook

This will create 4 VMs:
    Jumphost
    Host 1
    Host 2
    Host 3

Playbooks to:
    Clone (Create) VMs
    Start VMs
    Stop VMs
    Delete VMs


Run Command, eg:
ansible-playbook pve_start_vms_rmc.yaml  --user=root 

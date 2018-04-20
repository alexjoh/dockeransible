---
- name: Access Inventory Variable
  hosts: dockermasters
  connection: local
  tasks:
    - name: createVM from Template
      debug:
        var: hostvars[inventory_hostname]['ipaddr']
    - name: show hostname
      debug:
        msg: "hostname is {{ inventory_hostname }}"
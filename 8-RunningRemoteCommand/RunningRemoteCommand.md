---
- hosts: docker-manager-first
  remote_user: root
  pre_tasks:
    - include_tasks: tasks/load-vars.yml
  become: yes
  become_method: sudo
  tasks:
  - name: Get service list from Docker Manager node
    become: yes
    expect:
      command: ssh root@{{DockerManagerNode}} "docker service ls"
      responses:
        "password": "password"
        "yes": "yes"
    register: dockerSwarmServiceList

  - debug:
      var: dockerSwarmServiceList
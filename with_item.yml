---
- hosts: webservers
  become: true
  tasks:
  - name: Create multiple directories
    file: path={{item}} state=directory
    with_items:
    - '/home/vn1'
    - '/home/vn2'
    - '/home/vn3'

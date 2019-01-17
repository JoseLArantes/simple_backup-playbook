# Simple Backup (archive) playbook

#### For Ubuntu 16.04 and MySQL

Simple folder archive keeping 5 versions of files:
  - Install Ansible (2.5+)
  -- `sudo apt-add-repository ppa:ansible/ansible`
  -- `sudo apt install ansible`
  - Install python-pymysql
  -- `sudo apt install python-pymysql`
  - Adjust the paths and names on the files`.
  - Adjust the cron file and put it on `/etc/cron.d`.
  - Manually test it running `ansible-playbook simple_backup-playbook.yml`


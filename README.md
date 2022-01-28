# lab3
# Usage:
  - ansible-playbook install_httpd_fwd.yml
  - ansible-playbook remove_httpd_fwd.yml
  - ansible-playbook install_vsftpd.yml
[DEPRECATION WARNING]: Invoking "dnf" only once while using a loop via squash_actions is deprecated. Instead of using 
a loop to supply multiple items and specifying `name: "{{ item }}"`, please use `name: 'httpd, mod_ssl'` and remove 
the loop. This feature will be removed in version 2.11. Deprecation warnings can be disabled by setting 
deprecation_warnings=False in ansible.cfg.


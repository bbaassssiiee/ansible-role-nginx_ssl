nginx_ssl
=========

A role to install a reverse proxy for SSL termination.

Requirements
------------

Linux.

Role Variables
--------------

```yml
# defaults
desired_state: present  # or absent
verify_state: true  # or false
package: nginx  # or httpd
service: nginx  # or httpd
```

Dependencies
------------
None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: web
      roles:
         - role: bbaassssiiee.nginx_ssl
```

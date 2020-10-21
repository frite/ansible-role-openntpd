minimal_openntpd_config
=========

Minimal openNTPd configuration.


Role Variables
--------------
* List of NTP Servers.
  ```
  # default
  ntp_servers:
    - "servers 0.debian.pool.ntp.org"
    - "servers 1.debian.pool.ntp.org"
    - "servers 2.debian.pool.ntp.org"
    - "servers 3.debian.pool.ntp.org"
  ```
* Timezone
  ```
  # default
  timezone: "Etc/UTC"
  ```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: frite.minimal_openntpd_config }

License
-------

MIT

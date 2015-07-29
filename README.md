# ansible-role-docker-graphite
Ansible role with hopsoft/graphite-statsd container

# Directories
Metrics stored at ``/var/lib/graphite/whisper``, other data in container.

## Configs:
- /etc/graphite/carbon.conf
- /etc/graphite/storage-aggregation.conf
- /etc/graphite/storage-schemas.conf

# Sample playbook
```
- hosts: all
  roles:
    - ansible-role-docker-graphite
```

## TODO
- [ ] graphite HTTP authorization
- [ ] influxdb backend
- [ ] docker runner from hexlet.io

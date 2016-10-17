# satellite6

This repository contians different tools for Red Hat Satellite 6.

## ansible/sat6-migrate-hosts.yml 

This ansible playbook that can be used to migrate hosts between one Satellite capsule and another. Either one of them can be the internal capsule of the Satellite server. The playbook currently assumes that the hosts that are migrated are previously registered and already has a working Puppet configuration that can be altered. Also, it does not update the capsule settings on the hosts objects in the Satellite, it only make changes locally.

# Satellite
Playbook for Satellite Registration
Tested against Red Hat Satellite 6.2 - 6.5


This playbook requires few arguments:
- ip of the remote capsule
- hostname of the remote capsule
- activation key to use ( it must be created and configured before to use this playbook )
- organization name


It checks for network connectivity, proxy settings in yum/rhsm, in case of any katello/insight rpm already installed, it will delete those rpm and it will install the new ones from the new capsule



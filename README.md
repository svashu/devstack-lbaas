devstack-lbaas
==============
Devstack and LBAAS localrc

Prerequisites:
--------------
- DevStack setup requires to have 1 VM/ BM machine with internet connectivity.
- Setup a fresh supported Linux installation. (Ubuntu/Fedora/CentOs)
- Install Git

Steps
-----
Clone devstack
```
$git clone https://github.com/openstack-dev/devstack.git
```

Clone devstack-lbaas
```
$git clone https://github.com/svashu/devstack-lbaas.git
```

Copy localrc from devstack-lbaas to devstack
```
$ cp devstack-lbaas/localrc devstack

```

Modify the devstack/localrc for IP and password modifications

Deploy your Devstack

```
$cd devstack && ./stack.sh
```

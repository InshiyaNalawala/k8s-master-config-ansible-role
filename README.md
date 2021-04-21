Role Name
=========

Use this role to configure the kubernetes master node launched on AWS 

Requirements
------------

1. Provisioned instances on AWS (use the 'cluster' role - https://github.com/InshiyaNalawala/kubernetes-cluster/tree/master/roles/cluster )
2. Tag the master instance as - "kubernetes":"master"


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: tag_kubernetes_master
      roles:
         - role: k8s_master


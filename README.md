# kubernetescluster collection

This collection contains the roles for configuring the Kubernetes master and slave nodes. Currently, it supports Amazon Linux 2 and Redhat Enterprise Linux v8.

kube_master
-----------

This is the role for configuring Kubernetes master node. You can find more information about it in the kube_master/README.md file.

kube_slave
----------

This is the role for configuring Kubernetes slave node. You can find more information about it in the kube_slave/README.md file.

configure_master.yml
--------------------

This is the example playbook for using kube_master role

configure_slave.yml
-------------------

This is the example playbook for using kube_slave role

License
-------
MIT

Author
------
[Ankush Chavan](https://www.linkedin.com/in/ankushchavan)
K8S neutron
==========
[![Galaxy](https://img.shields.io/badge/galaxy-tripleo.k8s--neutron-blue.svg?style=flat)](https://galaxy.ansible.com/tripleo/k8s-neutron)
[![Build Status](https://travis-ci.org/tripleo/ansible-role-k8s-neutron.svg?branch=master)](https://travis-ci.org/tripleo/ansible-role-k8s-neutron)

Install neutron in a Kubernetes cluster.

Requirements
------------

Access to Kubernetes cluster

Role Variables
--------------

| Name              | Default Value       | Description          |
|-------------------|---------------------|----------------------|
| `action` | `provision` | List of tasks to run. |
| `core_host` |  |  |
| `kube_context` |  |  |
| `config_file` |  |  |


Dependencies
------------

- `ansible.kubernetes-modules`

Example Playbook
----------------

    - hosts: all
      roles:
         - tripleo.k8s-neutron

License
-------

Apache License v2

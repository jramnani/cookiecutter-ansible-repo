## {{ cookiecutter.project_name }}

{{ cookiecutter.project_description }}

This repository contains a skeleton directory layout for [Ansible].
It uses a directory layout specified in [Ansible Best Practices].


## Requirements

Ansible requires the following be installed on the machine running Ansible:

* Python 2.7
* Ansible must be installed. Here are [Ansible installation instructions].

Some requirements that are recommended to make development and testing easier.

* [virtualenv] - To keep your Python dependencies isolated.
* [Vagrant] - To create local virtual machines for testing roles and playbooks.
* [Molecule] - To manage virtual machines used to test a role.
* [Testinfra] - To write tests for roles and/or playbooks.


[Ansible]: https://ansible.com/
[Ansible Best Practices]: http://docs.ansible.com/ansible/playbooks_best_practices.html#directory-layout
[Ansible installation instructions]: http://docs.ansible.com/ansible/intro_installation.html
[Molecule]: https://molecule.readthedocs.io/
[Testinfra]: http://testinfra.readthedocs.io/
[Vagrant]: https://www.vagrantup.com/
[virtualenv]: http://virtualenv.readthedocs.org/

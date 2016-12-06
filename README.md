## cookiecutter-ansible-repo

This repository contains a [Cookiecutter] template that provides a skeleton project directory
for an [Ansible] repository.  It uses the directory layout described in [Ansible Best Practices].

Rather than using inventory files at the top-level directory as described in
[Ansible Best Practices] this directory layout uses an inventory directory that
contains an inventory file for a [Static Inventory].  You can add [Dynamic Inventory]
scripts into this directory for whichever provider you use (e.g.
Amazon EC2, Google Compute Engine, etc.).

Other than the static  inventory directory, no other decisions have been made
for you.  This are the essential files and directories to get started.


## Usage

* Install [Cookiecutter]. `$ pip install cookiecutter`
* `cd` into the directory you want to create the project in.
* Run this template. `$ cookiecutter gh:jramnani/cookiecutter-ansible-repo`


## License

This project is licensed using the MIT License. See the LICENSE file for details.


[Amazon Web Services EC2]: https://aws.amazon.com/ec2/
[Ansible]: https://www.ansible.com/
[Ansible Best Practices]: http://docs.ansible.com/ansible/playbooks_best_practices.html#directory-layout
[Cookiecutter]: http://cookiecutter.readthedocs.io/
[Static Inventory]: http://docs.ansible.com/ansible/intro_inventory.html
[Dynamic Inventory]: http://docs.ansible.com/ansible/intro_dynamic_inventory.html

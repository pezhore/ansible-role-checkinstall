# Ansible Role: Checkinstall

* Installs [Checkinstall](http://checkinstall.izto.org/)

## Requirements

  None.

## Role Variables

Basic configuration
````yaml
CHECKINSTALL_VERSION: "1.6.2" # Target Version
````

## Dependencies

None.

## Example Playbook

````
- hosts: localhost
  roles:
    - pezhore.golang
````

## Installation

* Install using `ansible-galaxy install git+https://github.com/pezhore/ansible-role-checkinstall.git`
* Add this role to your playbook.
* Modify above variables as desired.

## License

Apache 2.0

## Author Information

This role was created in 2020 by [Brian Marsh](https://github.com/pezhore).


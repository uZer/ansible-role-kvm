# kvm

Install kvm and manage bridge on archlinux with netctl.
This role is not ready for production.

### Usage

In playbook:

    - name: Playbook
      roles:
        - role: kvm

Include in `requirements.yml`:

    - src: https://github.com/uZer/ansible-role-kvm.git
      name: uZer.kvm
      version: latest

Install/Force update:

    ansible-galaxy install -r requirements.yml --force

### Variables

TBD.

### License

* `BY-SA` – [Attribution-ShareAlike](https://creativecommons.org/licenses/by-sa/4.0/)

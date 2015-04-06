# Bootstrap Mac OS X with Ansible pull

This project provides a script, which will help bootstrap fresh Mac OS X installations. If needed it will install Xcode Command Line Tools, Homebrew and Ansible. If this is in place, it will run [`ansible-pull`](http://docs.ansible.com/playbooks_intro.html#ansible-pull) with a user given repository.

To run the script, execute the following command:

```sh
$ ruby -e "$(curl -fsSL https://git.io/osx-ansible-bootstrap)"
```

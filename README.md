Macbook provisioning
=====
Ansible playbook for provisioning Macbook.

## Readying

```
$ sudo xcodebuild -license
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew install git
$ brew install ansible
```

## Usage

```
$ mkdir ~/.macbook-provisioning && cd $_
$ git clone git@github.com:shifumin/macbook-provisioning.git .
$ ansible-playbook -i hosts macbook.yml
```


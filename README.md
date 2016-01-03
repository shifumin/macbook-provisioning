Macbook provisioning
=====
Ansible playbook for provisioning Macbook.

## Stack

- defaults
- Homebrew
- Homebrew Cask
- Zsh
- Git
- tmux
- dotfiles
- Solarized
- Ruby


## Readying

```
$ sudo xcodebuild -license
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew install git
$ brew install ansible
```

## Usage

```
$ git clone git@github.com:shifumin/macbook-provisioning.git
$ cd macbook-provisioning
$ ansible-playbook -i hosts macbook.yml
```


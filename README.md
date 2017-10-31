Macbook provisioning
=====
Ansible playbook for provisioning Macbook.

## Operation Environment

- macOS High Sierra 10.13
- Python 2.7.14
- Ansible 2.4.1.0

## Stack

- osx_defaults
- Homebrew
- Homebrew Cask
- Git
- Zsh
- tmux
- dotfiles
- ghq
- git
- Karabiner-Elements
- Neovim
- Solarized
- Ruby


## Readying

```
$ git clone https://github.com/shifumin/macbook-provisioning
$ cd macbook-provisioning
$ ./setup_ansible.sh
```

## Usage

```
$ ansible-playbook -i hosts localhost.yml --ask-become-pass
```

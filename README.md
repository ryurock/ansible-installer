ansible-installer
=================

[Ansible](http://www.ansible.com/home) install Installer

This tools is used to install `ansible` and friends.

This plugin was inspired from [pyenv-installer](https://github.com/yyuu/pyenv-installer).

## Deppencecy

* zlib
* libyaml

### Install Deppencecy OSX

```shell
brew install homebrew/dupes/zlib
brew install libyaml
```

## Installation

Install [ansible](http://www.ansible.com/home) and friends by running:

```
curl https://raw.github.com/ryurock/ansible-installer/master/bin/setup | bash
# OSX
source ~/.bash_profile
# or
source ~/.bashrc

# Linux
source /etc/profile

```
## Version History

#### 20140226

 * Initial public release.

### License

(The MIT License)

* Copyright (c) 2014 Ryusuke Kimura

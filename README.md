# Etcdctl plugin for oh-my-zsh
This is an etcdctl autocomplete plugin for oh-my-zsh.

## Installation

First, install the etcd-completion rubygem. 
```
gem install etcd-completion
```
The next step varies depending on how you use zsh. Instructions included for antigen and oh-my-zsh.

### Antigen Install:
Install the bundle by editing your .zshrc file:
```bash
antigen bundle sheax0r/etcdctl-zsh
```

### Oh-my-zsh Install:

#### 1. Clone the git repository into your custom plugins directory:
```bash
git clone https://github.com/sheax0r/etcdctl-zsh.git ~/.zsh/custom/plugins/etcdctl-zsh
```

#### 2. Include the plugin in your .zshrc, along with your other plugins:
```bash
plugins=(...git vagrant etcdctl-zsh...)
```

## Usage
* Use etcdctl as usual: ```etcdctl <command> <path>```
* Autocompletion will function on commands.
* Autocompletion will function on paths too.

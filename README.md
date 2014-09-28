# Etcdctl plugin for oh-my-zsh
This is an etcdctl autocomplete plugin for oh-my-zsh.

## Installation
1. Clone the git repository into your custom plugins directory:
```bash
git clone https://github.com/sheax0r/etcdctl-oh-my-zsh.git ~/.zsh/custom/plugins/etcdctl
```

2. Install the etcd-completion rubygem:
```
gem install etcd-completion
```

3. Include the plugin in your .zshrc, along with your other plugins:
```bash
plugins=(git vagrant etcdctl)
```

4. Restart your shell:
```
exec $SHELL
```

## Usage
* Use etcdctl as usual: ```etcdctl <command> <path>```
* Autocompletion will function on commands.
* Autocompletion will function on paths too.

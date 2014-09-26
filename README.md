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
* Use etcdctl as usual: ```etc <command> <path>```
* Autocompletion will function on commands.
* Autocompletion will function on paths too.

## Features
* Aliases etcdctl to etc (etcdctl is really annoying to type repeatedly!)
* Recursively lists all children. I'd like to make it only list immediate potential
  matches until a slash is typed and then add more matches (you know, like how "ls" 
  works), but I only just learned how to do completion in zsh so bear with me.



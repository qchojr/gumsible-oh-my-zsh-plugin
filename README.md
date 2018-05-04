# Gumsible oh-my-zsh-plugin

### Using Oh-My-Zsh

If you are using Linux or Mac OS X, Oh-My-Zsh is a great tool to manage your ZSH configuration.

Most of the GumGum Ops team uses Oh-My-Zsh, and if you see people using shortcuts in their terminal, the magic comes from here!

### Oh-My-Zsh Gumsible plugin
The Gumsible Oh-My-Zsh plugin is available on GitHub at https://github.com/Lowess/gumsible-oh-my-zsh-plugin.

Currently it offers the following wrappers:

* `gumsible check`: Shortcut to run `molecule check`
* `gumsible converge`: Shortcut to run `molecule check`
* `gumsible create`: Shortcut to run `molecule check`
* `gumsible dependency`: Shortcut to run `molecule check`
* `gumsible destroy`: Shortcut to run `molecule check`
* `gumsible idempotence`: Shortcut to run `molecule check`
* `gumsible init`: Used to initialize new Ansible role from a template including the [Molecule](http://molecule.readthedocs.io/en/latest/index.html) test framework, [Pre-commit](https://pre-commit.com/) hooks and [Drone](http://docs.drone.io/) CI/CD pipeline.
* `gumsible lint`: Shortcut to run `molecule lint`
* `gumsible list`: Shortcut to run `molecule list`
* `gumsible login <host>`: Shortcut to run `molecule login`
* `gumsible molecule <cmd>`: Runs `molecule` commands
* `gumsible prepare`: Shortcut to run `molecule prepare`
* `gumsible side-effect`: Shortcut to run `molecule side-effect`
* `gumsible syntax`: Shortcut to run `molecule syntax`
* `gumsible test`: Shortcut to run `molecule test`
* `gumsible verify`: Shortcut to run `molecule verify`

It is not part of the official plugin list, so you need to install it manually:

* Edit your `~/.zshrc` and add `gumsible` to the list of plugins to enable:

`plugins=( ... gumsible )`

In the command line, change to oh-my-zsh’s custom plugin directory and clone the repository:

`cd ~/.oh-my-zsh/custom/plugins && git clone https://github.com/Lowess/gumsible-oh-my-zsh-plugin gumsible && cd && . ~/.zshrc`

zsh-gvm
=======

A gvm(Groovy enVironment Manager) plugin for oh my zsh

gvm project information available [here](http://gvmtool.net/)

The plugin provides auto-completion for gvm commands.

# Installation

## oh-my-zsh users

If you're using [oh-my-zsh](https://gitub.com/robbyrussell/oh-my-zsh), install this plugin by doing the following:

1. Go to your oh-my-zsh custom plugins directory - `cd ~/.oh-my-zsh/custom/plugins`

2. Clone the plugin into a new gvm directory - `git clone https://github.com/yerinle/zsh-gvm.git gvm`

3. Edit your `.zshrc` and add `plugins=( ... gvm )` to your list of plugins

4. Open a new terminal and enjoy!

## antigen users

If you're using [Antigen](https://github.com/zsh-lovers/antigen), install this plugin by doing the following:

1. Add `antigen bundle yerinle/zsh-gvm` to your `.zshrc` where you're adding your other plugins.
2. Either open a new terminal to force zsh to load the new plugin, or run `antigen bundle yerinle/zsh-gvm` in a running zsh session.
3. Enjoy!

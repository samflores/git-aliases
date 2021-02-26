# git-aliases

Consult [source file](git-aliases.plugin.zsh) for more details.


## Installation

### [zinit](https://github.com/zdharma/zinit)

```zsh
zinit load samflores/git-aliases
# or
zinit light samflores/git-aliases
```

### [zplug](https://github.com/zplug/zplug)

```zsh
zplug "samflores/git-aliases", use:git-aliases.plugin.zsh
```

### [Antigen](https://github.com/zsh-users/antigen)

```zsh
antigen bundle samflores/git-aliases.git
```

### Manual

Download the latest released `git-aliases.plugin.zsh` to `$ZSH/plugins/git-aliases`: 
```shell
curl --create-dirs -o $ZSH/plugins/git-aliases/git-aliases.plugin.zsh -sL \
$(curl -s https://api.github.com/repos/samflores/git-aliases/releases \
| grep browser_download_url \
| head -n 1 \
| cut -d '"' -f 4)
```

Add `git-aliases` to `plugins` in `$ZDOTDIR/.zshrc`.

Restart the shell.

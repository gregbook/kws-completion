# kws-completion

This plugin adds auto-completion for [kws](https://github.com/pipedrive/k8s-workstation) in a zsh.

## As an [Oh My ZSH!](https://github.com/robbyrussell/oh-my-zsh) custom plugin

Clone `kws-completion` into your custom plugins repo

```shell
git clone https://github.com/gregbook/kws-completion ~/.oh-my-zsh/custom/plugins/kws
```

To use it add `kws-completion` to the plugins array in your zshrc file.

```zsh
plugins+=(kws-completion)
```

Keep in mind that plugins need to be added before `oh-my-zsh.sh` is sourced.

## Manually

Clone this repository somewhere (`~/.kws-completion` for example)

```shell
git clone https://github.com/gregbook/kws-completion.git ~/.kws-completion
```

Then source it in your `.zshrc`

```shell
source ~/.kws-completion/_kws-completion
```

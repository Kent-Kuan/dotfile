install `zsh`(is default shell since macOS Catalina) and `powerlevel10k`[https://github.com/romkatv/powerlevel10k]

install zsh plugins: `zsh-syntax-highlighting`, `zsh-autosuggestions`, `zsh-completions`

**caution**
if gcloud-cli is installed via `brew`, should add below line to `~/.zshrc`
```
source "$(brew --prefix)/share/google-cloud-sdk/path.zsh.inc"
source "$(brew --prefix)/share/google-cloud-sdk/completion.zsh.inc"
```

### custom configure `~/.zshrc`
```
# enable terminal colors, add to ~/.zshrc
export CLICOLOR=1
export LSCOLORS=GxFxCxDxBxegedabagaced
```

```
# alias
alias kc=`kubectl`
```

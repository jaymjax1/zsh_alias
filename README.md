# zsh_alias
Copy the below items into your .zshrc file in your home directory:

```
alias c="clear"
alias ..="cd .."
alias ...="cd ../.."
alias gcom="git checkout master"
alias gb="git branch"
alias gs="git status"
alias gcob="git checkout -b"
alias gco="git checkout"
alias kafka="zookeeper-server-start /usr/local/etc/kafka/zookeeper.properties & kafka-server-start /usr/local/etc/kafka/server.properties" 


# NVM
export NVM_DIR=~/.nvm
source $(brew --prefix nvm)/nvm.sh

#rbenv
eval "$(rbenv init -)"
```

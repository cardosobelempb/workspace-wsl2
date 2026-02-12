## comandos

```bash
fdisk -l
df -h
free -m
shutdown -h now

ls -laF
```

## comandos default

```bash
export LS_OPTIONS='--color=auto'
alias ls='ls $LS_OPTIONS'
alias ll='ls $LS_OPTIONS'
alias l='ls $LS_OPTIONS'
alias rm='rm -i'
alias cp='cp -i'
alias mv='mv -i'

source .zshrc
```

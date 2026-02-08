## Wsl Initial

```basch
wsl --list --verbose
wsl --install -d Ubuntu-22.04
wsl.exe -d Ubuntu-22.04
wsl --unregister Ubuntu-22.04

wsl --set-default Ubuntu-22.04
explorer.exe Ubuntu-22.04
wsl --status
wsl --update
wsl --shutdown

wsl --distribution Ubuntu-22.04 --user surb
wsl --distribution Ubuntu-22.04 --user root

exit

wsl --export  Ubuntu-22.04 "C:\Users\Public\Documents\ubuntu.tar"
wsl --import  Ubuntu-22.04 "C:" "F:\ubuntu.tar"
```

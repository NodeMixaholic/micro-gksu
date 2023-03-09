# micro-gksu

non-bloated gksu setup guide.

## installation

* install the ssh-askpass-gnome package (debian-based systems) or equal package in other package managers
* add this to your .bashrc

```bash
alias gksu='sudo -S'
alias gksuui='ssh-askpass Sudo Password, Please. | gksu'
```

* refresh .bashrc in current session using

```bash
. ~/.bashrc
```

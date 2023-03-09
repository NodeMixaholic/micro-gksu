# micro-gksu

non-bloated gksu setup guide.

## installation

* add this to your .bashrc

```bash
alias gksu='sudo -S'
alias gksuui='ssh-askpass Sudo Password, Please. | gksu'
```

* refresh .bashrc in current session using

```bash
. ~/.bashrc
```

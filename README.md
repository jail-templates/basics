# Apache 2.4 (http only)
Bastille template to add some basic packages to the jail and supress annoying messages.

* Installs nano, wget, curl and htop
* Supresses useless and bloaty MOTD messages

## Bootstrap
```
bastille bootstrap https://github.com/jail-templates/basics
```

## Apply template
```
bastille template $JAIL jail-templates/basics
```

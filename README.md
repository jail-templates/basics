# Basics
Bastille template to add some basic packages to the jail and supress annoying messages.

* Installs nano, wget, curl and htop.
* Supresses useless MOTD messages.

## Bootstrap
```
bastille bootstrap https://github.com/jail-templates/basics
```

## Apply template
```
bastille template $JAIL jail-templates/basics
```

## Support
Templates will be maintained until their respective software version is end-of-life. Repositories will then be archived and removed from any meta-templates.

If you have a question, suggestion or find a bug, please let us know via an Issues in the relevant repository or send us an email.

## License
All templates are distributed under the 3-Clause BSD NON-AI License. See `LICENSE` in every template repository for more information.

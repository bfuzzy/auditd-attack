# auditd-attack
A Linux Auditd rule set mapped to MITRE's Attack Framework

![](https://github.com/bfuzzy/auditd-attack/blob/master/attack_map.png) 

## Disclaimer

Please ensure you test these rules prior to pushing them into production. This rule set is NOT meant to have all of its rules enabled all at once (although that'd be ideal) it is setup to serve as guidance toward increasing detection/hunting coverage. 

## WIKI

[WIKI](https://github.com/bfuzzy/auditd-attack/wiki/Audit-Event-Fields)


## Special Thanks To:

[Eric Gershman](https://github.com/EricGershman/auditd-examples)

[iase.disa.mil](https://iase.disa.mil/stigs/os/unix-linux/Pages/red-hat.aspx)

[cyb3rops](https://gist.github.com/Neo23x0/9fe88c0c5979e017a389b90fd19ddfee)

[ugurengin](https://gist.github.com/ugurengin/4d37ee83e87bc44291f8ae87a00504cd)

[checkraze](https://github.com/checkraze/auditd-rules/blob/master/auditd.rules)

[auditdBroFramework](https://github.com/set-element/auditdBroFramework/blob/master/system_config/audit.rules)

[@MITREattack](https://twitter.com/MITREattack)


## TODO
- [ ] Increase MITRE ATT&CK coverage
- [ ] Test rules across multiple flavors of Linux
- [ ] Determine performance impacts of the ruleset

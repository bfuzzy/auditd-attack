# auditd-attack
A Linux Auditd rule set mapped to MITRE's Attack Framework

![](https://github.com/bfuzzy/auditd-attack/blob/master/attack_map.png) 

## Disclaimer

Please ensure you test these rules prior to pushing them into production. Also, events related to sudo and file creation / deletion types of events...etc can be fairly noisy during day-to-day operations and I reccomend you disable them if you're not prepared to handle a large corpus of events, but are needed for detection / hunting purposes. 


## Special Thanks To:

[Eric Gershman](https://github.com/EricGershman/auditd-examples)

[iase.disa.mil](https://iase.disa.mil/stigs/os/unix-linux/Pages/red-hat.aspx)

[cyb3rops](https://gist.github.com/Neo23x0/9fe88c0c5979e017a389b90fd19ddfee)

[ugurengin](https://gist.github.com/ugurengin/4d37ee83e87bc44291f8ae87a00504cd)

[checkraze](https://github.com/checkraze/auditd-rules/blob/master/auditd.rules)

# auditd-attack
A Linux Auditd rule set mapped to MITRE's Attack Framework

![](https://github.com/bfuzzy/auditd-attack/blob/master/attack_map.png) 

## Disclaimer

Please ensure you test these rules prior to pushing them into production. Also, events related to sudo and file creation / deletion types of events...etc can be fairly noisy during day-to-day operations and I reccomend you disable them if you're not prepared to handle a large corpus of events, but are needed for detection / hunting purposes. 

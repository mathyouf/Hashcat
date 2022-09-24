# Hashcat Fun

https://github.com/hashcat/hashcat/blob/master/rules/dive.rule

https://github.com/praetorian-inc/Hob0Rules

https://github.com/danielmiessler/SecLists/tree/master/Passwords

Run: `hashcat -a 0 -m 1000 starter.hash Hob0Rules/wordlists/rockyou.txt  -r /usr/share/hashcat/rules/dive.rule -o cracked_starter.txt`
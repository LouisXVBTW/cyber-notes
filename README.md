# Placeholder
=======
# Notes
(Can't find all my old notes, rip)
## nmap
### Scans

⇒ nmap -sCV -aN output -vvv ip
⇒ nmap -sC -sV -aO nmap/name ip

#### Scripts

### **These are all stored in:**


> ls -al /usr/share/nmap/scripts/


### General vuln scans:
> nmap —script vuln ip
> nmap —script vulners ip

⇒ SMTP users enumeration

- nmap --script smtp-enum-users -p port ip

meterpreter > run post/windows/gather/hashdump

## Linux
[https://gtfobins.github.io](https://gtfobins.github.io/)

> PayloadsAllTheThings
> Linpeas

- [Linux -Privilege Escalation](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjW473VlpfvAhWTs3EKHWDSApQQjBAwBHoECAgQAQ&url=https%3A%2F%2Fgithub.com%2Fswisskyrepo%2FPayloadsAllTheThings%2Fblob%2Fmaster%2FMethodology%2520and%2520Resources%2FLinux%2520-%2520Privilege%2520Escalation.md&usg=AOvVaw3P5Nno5p3hSufep4msf_KQ)

### SUID:

> find / -perm 4000 2> /dev/null

# Windows

> PayloadsAllTheThings

- [Windows Privilege Escalation](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjW473VlpfvAhWTs3EKHWDSApQQjBAwA3oECAcQAQ&url=https%3A%2F%2Fgithub.com%2Fswisskyrepo%2FPayloadsAllTheThings%2Fblob%2Fmaster%2FMethodology%2520and%2520Resources%2FWindows%2520-%2520Privilege%2520Escalation.md&usg=AOvVaw1w6PB_9_YBPlO5rhvgT2jd)

> Sticky notes

- Shells
    
    > PayloadsAllTheThings
    
    - [Reverse Shell Cheat Sheet](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Reverse%20Shell%20Cheatsheet.md)

# Notes

## nmap
### Scans

⇒ nmap -sCV -aN output -vvv ip

#### Scripts

### **These are all stored in:**


> ls -al /usr/share/nmap/scripts/


### General vuln scans:
> nmap —script vuln ip
> nmap —script vulners ip

⇒ SMTP users enumeration

- nmap --script smtp-enum-users -p port ip

meterpreter > run post/windows/gather/hashdump

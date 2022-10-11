# Thailand-Cyber-Top-Talent-2022
# network_security

network_security01
```bash

1 binwalk -e network_security01.pcap

2 extract zip file password

flag : tctt2022{Steal_Data_via_FTP}
```

network_security02
```bash

1 binwalk -e network_security02.pcap

2 extract zip file P@ssw0rd

flag : tctt2022{Welcome_R00t_T3ln3t}
```

# Programning


programming-challenge02.md
```bash
1 unzip program-challenge02.zip
2 python3 exploit.py | base64 -d | grep -o -E 'tctt2022{(.*?)}'

flag : tctt2022{r3P37i7Iv3_745K5_N33d_4U7Om47IoN}
```

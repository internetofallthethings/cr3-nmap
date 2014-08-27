Crimson v3 NMAP Script Repository
=================================

This is a repository for nmap NSE scripts related to the ICS HMI touchpanels
made by Red Lion Controls (http://redlion.net). These devices support updates
over TCP port 789. 

Twitter: @InternetOfAll  
Email:   thoughtleader /@@/ internetofallthethings.com  
Web:     http://blog.internetofallthethings.com  

Scripts
-------

+ cr3-fingerprint.nse : Hosts with TCP:789 open will be fingerprinted

```
Nmap scan report for redlion.example.com (127.0.0.1)
Host is up (0.14s latency).
Not shown: 1021 filtered ports
PORT    STATE SERVICE
80/tcp  open  http
502/tcp open  asa-appl-proto
789/tcp open  unknown
| cr3-fingerprint: 
| Manufacturer: Red Lion Controls
|_Model: G310C2
```


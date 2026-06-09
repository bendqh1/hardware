If disabling VoLTE had no effect:

- Set APN to `internet`  
- APN type: `default,supl,dun` (or `default,hipri,dun`)  
- APN protocol: IPv4/IPv6
- Reset network settings + recreate APN  
- Lock network to **4G only** (avoid congested 5G)  
- Change hotspot to **2.4 GHz**  
- Set **TTL to 65** (can bypass hotspot detection in some cases)
- Test SIM in another phone  
- Contact True to reprovision SIM / check FUP

**If still ~90 KB/h then probably it's a hard throttle by plan. Only fix: upgrade or buy add-on.**

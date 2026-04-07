# No Internet Connectivity

## 🛠 Problem
Cannot browse websites, ping fails

## 🔍 Steps
1. Check physical cable or WiFi connection
2. Run `ipconfig` — check if IP address is assigned
3. Ping the default gateway `ping 192.168.1.1`
4. Ping Google DNS `ping 8.8.8.8`
5. Ping a domain `ping google.com`

## ✅ Diagnosis Tips
- If ping 8.8.8.8 works but ping google.com fails → DNS issue
- If ping gateway fails → local network issue
- If all pings fail → check NIC or router

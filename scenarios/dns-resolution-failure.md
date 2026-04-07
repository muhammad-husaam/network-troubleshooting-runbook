# DNS Resolution Failure

## 🛠 Problem
User reports that websites do not load, but internet connectivity via IP addresses works.

---

## 🔍 Diagnosis Steps

1. Verify IP connectivity:
   ```bash
   ping 8.8.8.8

Test DNS resolution:

nslookup google.com

Check DNS server settings:

ipconfig /all

Flush DNS cache:

ipconfig /flushdns
Optional: Change DNS server to Google 8.8.8.8 or Cloudflare 1.1.1.1 and test again
✅ Solution
Corrected DNS server settings
Flushed DNS cache
Verified domain name resolution was successful

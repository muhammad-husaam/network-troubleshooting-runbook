# IP Address Issue

## 🛠 Problem
The system has no IP assigned or shows a 169.254.x.x address, indicating it could not obtain an IP from the DHCP server.

---

## 🔍 Diagnosis Steps

1. Check current IP configuration:
```bash
ipconfig
Release the current IP and renew:
ipconfig /release
ipconfig /renew
Verify the DHCP server is running and reachable.
If needed, assign a static IP manually and test connectivity.
✅ Solution
Renewed IP successfully via DHCP
Verified correct IP assignment with ipconfig /all
Ensured the DHCP server is active
Configured static IP as fallback when necessary

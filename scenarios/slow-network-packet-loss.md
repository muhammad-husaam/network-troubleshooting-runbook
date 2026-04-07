---
## Slow Network / Packet Loss

## 🛠 Problem
Internet browsing is slow, streaming buffers, or high latency observed.

---

## 🔍 Diagnosis Steps

1. Run continuous ping to test packet loss:
```bash
ping 8.8.8.8 -t
Run traceroute to identify network delays:
tracert google.com
Check bandwidth-heavy applications running in background
Restart router and modem
✅ Solution
Closed high-bandwidth apps
Restarted router and modem
Verified normal speed after fixes

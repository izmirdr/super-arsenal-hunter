# 🎯 yahoo — yahoo.com
**Date:** Sun May 10 02:59:39 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 53 |
| Live Hosts | 26 |
| URLs | 993 |
| Interesting Subs | 0 |
| IDOR Candidates | 0
0 |
| API Endpoints | 5 |
| JS Secrets | 0
0 |
| SSRF Candidates | 20 |
| Deep: SSRF Tests | 0 |
| Deep: Staging Hits | 0 |
| Deep: IDOR Suspects | 0 |
| Deep: Cache Checks | 5 |
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```

```

## Live Hosts
```
https://3p-udc.yahoo.com [403] [Yahoo! - Error report]
https://blog.360.yahoo.com [301] [Yahoo]
https://3d.yahoo.com [404] [Yahoo]
https://360.yahoo.com [301] [Yahoo]
https://ca.blog.360.yahoo.com [301] [Yahoo]
https://3p-geo.yahoo.com [404] [Yahoo - 404 Not Found]
https://fr.360.yahoo.com [404] [Yahoo]
https://de.blog.360.yahoo.com [301] [Yahoo]
https://fr.blog.360.yahoo.com [301] [Yahoo]
https://hk.7-eleven.yahoo.com [404] [Yahoo]
```

## IDOR Candidates
```

```

## API Endpoints
```
https://apis.mail.yahoo.com/ws/v3/mailboxes/@.id==VjN-vq6obj7Pb-b3VZVZrQUO6rx5RQeKokwbVR0YmOFQzpt4dIASW9fPGpu7kNEhy3pO7Km04qInWSFpqMxBpbwemw/messages/@.id==AGAvops5o6PIXE3ZYwYDEJFT4T4/content/parts/@.id
https://consent.yahoo.com/v2/collectConsent?sessionId=3_cc-session_0d49f765-b75d-4d1c-bb66-89939498f871
https://consent.yahoo.com/v2/collectConsent?sessionId=3_cc-session_dbb527d4-fab2-4b78-abe7-3b08cf85ccb2
https://query1.finance.yahoo.com/v7/finance/options/
https://query1.finance.yahoo.com/v7/finance/quote
```

## JS Secrets
```

```

## SSRF Candidates
```
http://www.yahoo.com/*http:/us.rd.yahoo.com/my/atm/CNN/HEALTH/*http:/us.rd.yahoo.com/evt=32777/*http:/add.my.yahoo.com/rss?url=http://rss.cnn.com/rss/cnn_health.rss
http://www.yahoo.com/*http:/us.rd.yahoo.com/my/atm/CNN/RECENT/*http:/us.rd.yahoo.com/evt=32777/*http:/add.my.yahoo.com/rss?url=http://rss.cnn.com/rss/cnn_latest.rss
http://www.yahoo.com/*http:/us.rd.yahoo.com/my/atm/CNN/TECH/*http:/us.rd.yahoo.com/evt=32777/*http:/add.my.yahoo.com/rss?url=http://rss.cnn.com/rss/cnn_tech.rss
http://www.yahoo.com/*http:/us.rd.yahoo.com/my/atm/CNN/UNDERSCORED/*http:/us.rd.yahoo.com/evt=32777/*http:/add.my.yahoo.com/rss?url=http://rss.cnn.com/cnn-underscored
http://www.yahoo.com/*http:/us.rd.yahoo.com/my/atm/CNN/US/*http:/us.rd.yahoo.com/evt=32777/*http:/add.my.yahoo.com/rss?url=http://rss.cnn.com/rss/cnn_us.rss
http://www.yahoo.com/*http:/us.rd.yahoo.com/my/atm/SI/TOPSTORIES/*http:/add.my.yahoo.com/rss?url=http://obitkansas.com/RSS/0
http://www.yahoo.com/*http:/us.rd.yahoo.com/my/atm/SI/TOPSTORIES/*http:/add.my.yahoo.com/rss?url=http://obitkansas.com/RSS/27
http://www.yahoo.com/*http:/us.rd.yahoo.com/my/atm/SI/TOPSTORIES/*http:/add.my.yahoo.com/rss?url=http://obitmissouri.com/RSS/0
http://www.yahoo.com/*http:/us.rd.yahoo.com/my/atm/SI/TOPSTORIES/*http:/add.my.yahoo.com/rss?url=http://obitmissouri.com/RSS/27
http://www.yahoo.com/?doit=done&amp;amp;url=http://sdp.ppona.com/&amp;amp;lp=en_de
```

## Nuclei
```

```

## 🔥 Deep Exploitation (Verified)

### SSRF Validation
```

```

### Staging/Dev Accessible
```

```

### IDOR Verified
```

```

### Cache Poisoning
```
XFH-Scheme: https://3p-udc.yahoo.com [403]
XFH-Scheme: https://blog.360.yahoo.com [404]
XFH-Scheme: https://3d.yahoo.com [404]
XFH-Scheme: https://360.yahoo.com [404]
XFH-Scheme: https://ca.blog.360.yahoo.com [404]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

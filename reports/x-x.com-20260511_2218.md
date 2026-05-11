# 🎯 x — x.com
**Date:** Mon May 11 22:18:49 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 726 |
| Live Hosts | 13 |
| URLs | 472 |
| Interesting Subs | 50 |
| IDOR Candidates | 0
0 |
| API Endpoints | 0
0 |
| JS Secrets | 0
0 |
| SSRF Candidates | 0
0 |
| Deep: SSRF Tests | 0 |
| Deep: Staging Hits | 0 |
| Deep: IDOR Suspects | 0 |
| Deep: Cache Checks | 7 |
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
about-dev.x.com
admin.help.x.com
admin.lab.money-dev.x.com
admin.lab.payments-dev.x.com
admin.money-dev-onprem.x.com
admin.money-dev.money-dev1.x.com
admin.money-dev.money-dev2.x.com
admin.money-dev.money-dev3.x.com
admin.money-dev.x.com
admin.money-dev1.x.com
admin.money-dev2.x.com
admin.money-dev3.x.com
admin.money-staging.x.com
admin.money.x.com
admin.payments-dev.x.com
```

## Live Hosts
```
https://ads-api.x.com [404]
https://about.x.com [302] [302 Found]
https://about-dev.x.com [404]
https://ads-staging.x.com [404]
https://ads.x.com [302]
https://advertising.x.com [301]
https://aa.x.com [404]
https://analytics.x.com [307]
https://api-stream.x.com [404]
https://amplify.x.com [301]
```

## IDOR Candidates
```

```

## API Endpoints
```

```

## JS Secrets
```

```

## SSRF Candidates
```

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
XFH-Scheme: https://ads-api.x.com [404]
CacheCand: https://about.x.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://about.x.com [302]
XFH-Scheme: https://about-dev.x.com [404]
XFH-Scheme: https://ads-staging.x.com [404]
CacheCand: https://ads.x.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://ads.x.com [302]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

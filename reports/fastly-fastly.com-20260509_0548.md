# 🎯 fastly — fastly.com
**Date:** Sat May  9 05:48:10 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 166 |
| Live Hosts | 53 |
| URLs | 500 |
| Interesting Subs | 37 |
| IDOR Candidates | 0
0 |
| API Endpoints | 30 |
| JS Secrets | 0
0 |
| SSRF Candidates | 0
0 |
| Deep: SSRF Tests | 0 |
| Deep: Staging Hits | 0 |
| Deep: IDOR Suspects | 0 |
| Deep: Cache Checks | 9 |
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
admin-compute.fastly.com
admin.fastly.com
api.fastly.com
beta-community.fastly.com
beta.fastly.com
branch-demos.developer.fastly.com
branch-doc-11440-address-ngwaf-api-confusion.developer.fastly.com
canary.api.fastly.com
cap-api.fastly.com
debug.fastly.com
demo-issuer.private-access-tokens.fastly.com
demo.stream.fastly.com
dev-confluence.corp.fastly.com
dev-jira.corp.fastly.com
developer.fastly.com
```

## Live Hosts
```
https://atlas.fastly.com [301]
https://canary.api.fastly.com [301]
https://app.fastly.com [403]
https://blog.fastly.com [302]
https://cfg.fastly.com [301]
https://connect.fastly.com [301]
https://developer.fastly.com [308]
https://accounts.fastly.com [307]
https://cap-api.fastly.com [404]
https://assets.fastly.com [404]
```

## IDOR Candidates
```

```

## API Endpoints
```
https://docs.fastly.com/api/
https://docs.fastly.com/api/account.html
https://docs.fastly.com/api/analytics.html
https://docs.fastly.com/api/auth.html
https://docs.fastly.com/api/clients.html
https://docs.fastly.com/api/config.html
https://docs.fastly.com/api/dynamicservers
https://docs.fastly.com/api/imageopto/
https://docs.fastly.com/api/imageopto/auto
https://docs.fastly.com/api/imageopto/bg-color
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
CacheCand: https://atlas.fastly.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://atlas.fastly.com [301]
CacheCand: https://canary.api.fastly.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://canary.api.fastly.com [301]
XFH-Scheme: https://app.fastly.com [200]
CacheCand: https://blog.fastly.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://blog.fastly.com [302]
CacheCand: https://cfg.fastly.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://cfg.fastly.com [301]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

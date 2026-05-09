# 🎯 mozilla — mozilla.org
**Date:** Sat May  9 15:47:03 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 1523 |
| Live Hosts | 35 |
| URLs | 981 |
| Interesting Subs | 50 |
| IDOR Candidates | 3 |
| API Endpoints | 4 |
| JS Secrets | 0
0 |
| SSRF Candidates | 0
0 |
| Deep: SSRF Tests | 0 |
| Deep: Staging Hits | 0 |
| Deep: IDOR Suspects | 2 |
| Deep: Cache Checks | 10 |
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
account.bcd.developer.mozilla.org
account.developer.mozilla.org
admin.addons.mozilla.org
admin.bugzilla.mozilla.org
admin.download.mozilla.org
alpha.bugzilla.mozilla.org
api-dev.bugzilla.mozilla.org
api.archive.mozilla.org
api.commonvoice.mozilla.org
api.developer.mozilla.org
api.mig-stage.security.mozilla.org
api.mig.mozilla.org
api.pub.build.mozilla.org
app.developer.mozilla.org
aretestsfastyet.performance.mozilla.org
```

## Live Hosts
```
https://admin.bugzilla.mozilla.org [302]
https://alpha.bugzilla.mozilla.org [302]
https://ads-img.mozilla.org [301]
https://air.mozilla.org [301] [301 Moved Permanently]
https://ai.mozilla.org [301] [301 Moved Permanently]
https://api-dev.bugzilla.mozilla.org [302]
https://advertising.mozilla.org [301] [301 Moved Permanently]
https://addons.mozilla.org [301]
https://accounts.mozilla.org [301] [301 Moved Permanently]
https://archive.mozilla.org [200] [Directory Listing: /]
```

## IDOR Candidates
```
https://www.mozilla.org/?id=19541
https://www.mozilla.org/?id=21122
https://www.mozilla.org/ca/?from=sfx&uid=0&t=572
```

## API Endpoints
```
http://download-stats.mozilla.org/stub/v8/beta/beta/mk/
http://download-stats.mozilla.org/stub/v8/release/release/de/1/1/10/0/19044/0/0/0/2/0/64739520/64739520/0/0/3/0/2/1/74/15/0/0/1/136.0.2/20250317120031/127.0/20240606181944/1/1/0/1/151.101.3.19/0/0/0
http://download-stats.mozilla.org/stub/v8/release/release/en-US/1/1/10/0/19044/0/0/0/2/0/64747832/64747832/0/0/4/0/3/1/84/15/0/0/1/136.0.2/20250317120031/127.0/20240606181944/1/1/0/1/151.101.131.19/0/0/0
https://links.email.mozilla.org/eos/v1/WHNPdUtHdTdOU2FlUmZQSFU1MUJDN3NtUzhsbFAyVnlHTnd1M3FBQ3RrL0c5Z0JtTjFJcW5yRGMyRHRwK0M4TWVYZnVCS3FGVTVzdDd2WE41OFZvd1ZKRWFLSFNaZmRXSXc3OFdWNFFjSEVXYzZ0MVE4bzVuWE4zN1ltQVY1UCtBdENIVFhsVlRWTzllNHY0RlhMT0V5eXZubGo0aURZaVdJeXN1Ry8rdUlNPQS2
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
IDOR-SUSPECT: https://www.mozilla.org/?id=19541 (48393b) vs https://www.mozilla.org/?id=19542 (48393b) [diff=0]
IDOR-SUSPECT: https://www.mozilla.org/?id=21122 (48393b) vs https://www.mozilla.org/?id=21123 (48393b) [diff=0]
```

### Cache Poisoning
```
CacheCand: https://admin.bugzilla.mozilla.org responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://admin.bugzilla.mozilla.org [302]
CacheCand: https://alpha.bugzilla.mozilla.org responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://alpha.bugzilla.mozilla.org [302]
CacheCand: https://ads-img.mozilla.org responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://ads-img.mozilla.org [301]
CacheCand: https://air.mozilla.org responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://air.mozilla.org [301]
CacheCand: https://ai.mozilla.org responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://ai.mozilla.org [301]
```

### CDN Bypass / Origin Discovery
```
CDN-BYPASS: admin.bugzilla.mozilla.org → origin.admin.bugzilla.mozilla.org (146.75.93.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: admin.bugzilla.mozilla.org → direct.admin.bugzilla.mozilla.org (146.75.93.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: admin.bugzilla.mozilla.org → backend.admin.bugzilla.mozilla.org (146.75.93.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: admin.bugzilla.mozilla.org → app.admin.bugzilla.mozilla.org (146.75.93.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: admin.bugzilla.mozilla.org → prod.admin.bugzilla.mozilla.org (151.101.73.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: alpha.bugzilla.mozilla.org → origin.alpha.bugzilla.mozilla.org (151.101.73.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: alpha.bugzilla.mozilla.org → direct.alpha.bugzilla.mozilla.org (151.101.73.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: alpha.bugzilla.mozilla.org → backend.alpha.bugzilla.mozilla.org (151.101.73.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: alpha.bugzilla.mozilla.org → app.alpha.bugzilla.mozilla.org (146.75.93.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: alpha.bugzilla.mozilla.org → prod.alpha.bugzilla.mozilla.org (146.75.93.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: api-dev.bugzilla.mozilla.org → origin.api-dev.bugzilla.mozilla.org (151.101.73.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: api-dev.bugzilla.mozilla.org → direct.api-dev.bugzilla.mozilla.org (151.101.73.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: api-dev.bugzilla.mozilla.org → backend.api-dev.bugzilla.mozilla.org (151.101.73.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: api-dev.bugzilla.mozilla.org → app.api-dev.bugzilla.mozilla.org (151.101.73.91) [orig:421/291b vs CDN:302]
CDN-BYPASS: api-dev.bugzilla.mozilla.org → prod.api-dev.bugzilla.mozilla.org (151.101.73.91) [orig:421/291b vs CDN:302]
```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

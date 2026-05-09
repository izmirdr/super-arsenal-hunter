# 🎯 reddit — reddit.com
**Date:** Sat May  9 02:13:05 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 3000 |
| Live Hosts | 99 |
| URLs | 271 |
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
| Deep: Cache Checks | 10 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
*.staging-business.reddit.com
2018coronavirusbeta-gnnusa.reddit.com
2fold.reddit.com
_dmarc.old.reddit.com
_mta-sts.old.reddit.com
a.ns.email.reddit.com
a.old.reddit.com
acapi.reddit.com
acesso.reddit.com
adadmin.reddit.com
admin.buttons.reddit.com
admin.dev.reddit.com
admin.embed.reddit.com
admin.m.reddit.com
admin.old.reddit.com
```

## Live Hosts
```
https://reddit.com [301]
https://ads-partner.reddit.com [301]
https://06.reddit.com [301]
https://1.reddit.com [301]
https://00-09.reddit.com [301]
https://1017coronavirus.reddit.com [301]
https://00.reddit.com [301]
https://0xproject.reddit.com [301]
https://03.reddit.com [301]
https://00-04.reddit.com [301]
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
CacheCand: https://reddit.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://reddit.com [301]
CacheCand: https://ads-partner.reddit.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://ads-partner.reddit.com [301]
CacheCand: https://06.reddit.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://06.reddit.com [301]
CacheCand: https://1.reddit.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://1.reddit.com [301]
CacheCand: https://00-09.reddit.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://00-09.reddit.com [301]
```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

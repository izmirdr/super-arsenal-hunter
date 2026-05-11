# 🎯 wordpress — wordpress.org
**Date:** Mon May 11 02:42:36 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 3000 |
| Live Hosts | 100 |
| URLs | 961 |
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
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
11ruepapillon.wordpress.org
2010dev.wordpress.org
253aapi.wordpress.org
2fdeveloper.wordpress.org
3aapi.wordpress.org
3holargou.wordpress.org
40api.wordpress.org
_cuplogin._tcp.planet.wordpress.org
_cuplogin._tcp.profiles.wordpress.org
_cuplogin._tcp.wordpress.org
_cuplogin.planet.wordpress.org
_cuplogin.profiles.wordpress.org
_cuplogin.wordpress.org
a.ns.email.wordpress.org
acapi.planet.wordpress.org
```

## Live Hosts
```
https://100.wordpress.org [301]
https://03.wordpress.org [301]
https://112.wordpress.org [429] [429 Too Many Requests]
https://119.wordpress.org [301]
https://117.wordpress.org [429] [429 Too Many Requests]
https://106.wordpress.org [429] [429 Too Many Requests]
https://11ruepapillon.wordpress.org [301]
https://123.wordpress.org [429] [429 Too Many Requests]
https://110.wordpress.org [429] [429 Too Many Requests]
https://1234.wordpress.org [429] [429 Too Many Requests]
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
CacheCand: https://100.wordpress.org responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://100.wordpress.org [301]
CacheCand: https://03.wordpress.org responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://03.wordpress.org [301]
CacheCand: https://112.wordpress.org responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://112.wordpress.org [301]
CacheCand: https://119.wordpress.org responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://119.wordpress.org [301]
CacheCand: https://117.wordpress.org responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://117.wordpress.org [301]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

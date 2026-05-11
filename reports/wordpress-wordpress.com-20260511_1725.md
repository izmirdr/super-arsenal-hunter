# 🎯 wordpress — wordpress.com
**Date:** Mon May 11 17:25:35 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 160 |
| Live Hosts | 91 |
| URLs | 492 |
| Interesting Subs | 9 |
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
| Deep: Cache Checks | 8 |
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
*.dev.dfw.wordpress.com
--pezagenderanddevelopment.wordpress.com
abrilquatrorodas.wordpress.com
betadailytelegraphatnewscorpau.wordpress.com
dev.dfw.wordpress.com
goldcoastbulletinnewscorpau.wordpress.com
gqatnewscorpau.wordpress.com
www.betadailytelegraphatnewscorpau.wordpress.com
www.goldcoastbulletinnewscorpau.wordpress.com
```

## Live Hosts
```
https://support.wordpress.com [301] [301 Moved Permanently]
https://000000000000000000000000000000000000000000j10okrion.wordpress.com [410]
https://abrilsuperinteressante.wordpress.com [410]
https://search.wordpress.com [301] [301 Moved Permanently]
https://ciuleandra2.0.wordpress.com [302]
https://abrilquatrorodas.wordpress.com [410]
https://cairnspostnewscorpau.wordpress.com [410]
https://adelaidenownewscorpau.wordpress.com [410]
https://support.files.wordpress.com [302] [302 Found]
https://0000ressentiment.wordpress.com [200] [直結産地るさんちまん]
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
CacheCand: https://support.wordpress.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://support.wordpress.com [301]
XFH-Scheme: https://000000000000000000000000000000000000000000j10okrion.wordpress.com [410]
XFH-Scheme: https://abrilsuperinteressante.wordpress.com [410]
CacheCand: https://search.wordpress.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://search.wordpress.com [301]
CacheCand: https://ciuleandra2.0.wordpress.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://ciuleandra2.0.wordpress.com [302]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

# 🎯 expressvpn — expressvpn.com
**Date:** Mon May 11 06:50:42 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 246 |
| Live Hosts | 21 |
| URLs | 644 |
| Interesting Subs | 50 |
| IDOR Candidates | 0
0 |
| API Endpoints | 1 |
| JS Secrets | 0
0 |
| SSRF Candidates | 2 |
| Deep: SSRF Tests | 0 |
| Deep: Staging Hits | 0 |
| Deep: IDOR Suspects | 0 |
| Deep: Cache Checks | 6 |
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
*.prod-rewrite.portal.expressvpn.com
*.staging-cdn-com.checkout.expressvpn.com
*.staging-pr-1000.portal.expressvpn.com
*.staging-pr-133.portal.expressvpn.com
*.staging-pr-168.portal.expressvpn.com
*.staging-pr-172.portal.expressvpn.com
*.staging-pr-293.checkout.expressvpn.com
*.staging-pr-62.portal.expressvpn.com
*.staging-pr-965.portal.expressvpn.com
*.staging-pr-981.portal.expressvpn.com
*.staging-pr-988.portal.expressvpn.com
*.staging-renue-integration.checkout.expressvpn.com
*.staging-rewrite.portal.expressvpn.com
*.staging.portal.expressvpn.com
admin@expressvpn.com
```

## Live Hosts
```
https://prod-rewrite.portal.expressvpn.com [403] [Attention Required! | Cloudflare]
https://admin@expressvpn.com [301]
https://staging-rewrite.portal.expressvpn.com [401]
https://staging.portal.expressvpn.com [401]
https://cdn.portal.expressvpn.com [404] [Not Found]
https://staging-renue-integration.checkout.expressvpn.com [403] [Attention Required! | Cloudflare]
https://checkout.expressvpn.com [308]
https://connectivitycheck.expressvpn.com [200] [VPN Status]
https://auth.expressvpn.com [302]
https://api-v2-jwks.integration.expressvpn.com [403]
```

## IDOR Candidates
```

```

## API Endpoints
```
https://portal.expressvpn.com/api/invoices/180506260/download
```

## JS Secrets
```

```

## SSRF Candidates
```
https://www.expressvpn.com/404?desturl=https%3A%2F%2Fwww.expressvpn.com%2F
https://www.expressvpn.com/affiliates/scripts/click.php?a_aid=stoneycase&desturl=https%3A%2F%2Fwww.expressvpn.com%2F
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
XFH-Scheme: https://prod-rewrite.portal.expressvpn.com [403]
CacheCand: https://admin@expressvpn.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://admin@expressvpn.com [301]
XFH-Scheme: https://staging-rewrite.portal.expressvpn.com [401]
XFH-Scheme: https://staging.portal.expressvpn.com [401]
XFH-Scheme: https://cdn.portal.expressvpn.com [404]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

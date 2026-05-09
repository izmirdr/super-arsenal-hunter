# 🎯 coinbase — coinbase.com
**Date:** Sat May  9 06:30:17 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 743 |
| Live Hosts | 35 |
| URLs | 500 |
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
*.console.cloud.coinbase.com
*.developer.coinbase.com
*.sandbox.prime.coinbase.com
*.sandbox.pro.coinbase.com
account.api.wallet.coinbase.com
admin.accounts.coinbase.com
ads.graphql.coinbase.com
alpha.chain-proxy.wallet.coinbase.com
api-n5e1.coinbase.com
api-public.pro--coinbase.com
api-public.sandbox.exchange.coinbase.com
api-public.sandbox.pro.coinbase.com
api-test.prime.coinbase.com
api.am.coinbase.com
api.cdp.coinbase.com
```

## Live Hosts
```
https://institutional.coinbase.com [302]
https://console.cloud.coinbase.com [301]
https://coinbase.com [302]
https://cloud.coinbase.com [302]
https://developer.coinbase.com [301]
https://cdp.coinbase.com [302]
https://commerce.coinbase.com [302]
https://international.coinbase.com [200] [Coinbase International Exchange]
https://178281coinbase.com [403] [Just a moment...]
https://exchange.coinbase.com [200] [Coinbase Exchange | Institutional Trading Platform]
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
CacheCand: https://institutional.coinbase.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://institutional.coinbase.com [302]
CacheCand: https://console.cloud.coinbase.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://console.cloud.coinbase.com [301]
CacheCand: https://coinbase.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://coinbase.com [302]
CacheCand: https://cloud.coinbase.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://cloud.coinbase.com [302]
CacheCand: https://developer.coinbase.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://developer.coinbase.com [301]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

# 🎯 salesforce — salesforce.com
**Date:** Tue May 12 14:20:46 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 769 |
| Live Hosts | 10 |
| URLs | 984 |
| Interesting Subs | 50 |
| IDOR Candidates | 0
0 |
| API Endpoints | 1 |
| JS Secrets | 0
0 |
| SSRF Candidates | 1 |
| Deep: SSRF Tests | 0 |
| Deep: Staging Hits | 0 |
| Deep: IDOR Suspects | 0 |
| Deep: Cache Checks | 5 |
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
*.developer.salesforce.com
*.development.developer.salesforce.com
*.development.trailhead.salesforce.com
*.dfc-org-development.developer.salesforce.com
*.dfc-org-development.startups.salesforce.com
*.dfc-org-production.developer.salesforce.com
*.dfc-org-qa.developer.salesforce.com
*.dfc-org-qa.startups.salesforce.com
*.dfc-org-staging.developer.salesforce.com
*.dfc-org-staging.startups.salesforce.com
*.docs.developer.salesforce.com
*.production.developer.salesforce.com
*.qa.developer.salesforce.com
*.qa.startups.salesforce.com
*.qa.trailhead.salesforce.com
```

## Live Hosts
```
https://bloom.salesforce.com [] [Fastly error: unknown domain bloom.salesforce.com]
https://staging.startups.salesforce.com [] [Fastly error: unknown domain staging.startups.salesforce.com]
https://staging.bloom.salesforce.com [] [Fastly error: unknown domain staging.bloom.salesforce.com]
https://developer.salesforce.com [403]
https://docs.developer.salesforce.com [421]
https://startups.salesforce.com [301]
https://qa.developer.salesforce.com [403]
https://staging.admin.salesforce.com [403]
https://staging.developer.salesforce.com [403]
https://trailhead.salesforce.com [200] [Trailhead | The fun way to learn]
```

## IDOR Candidates
```

```

## API Endpoints
```
https://kv7kzm78.api.commercecloud.salesforce.com/product/products/v1/organizations/f_ecom_zzte_053/
```

## JS Secrets
```

```

## SSRF Candidates
```
https://catalina.my.salesforce.com/a6aUz000000B0KrIAKurl=
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
XFH-Scheme: https://bloom.salesforce.com [500]
XFH-Scheme: https://staging.startups.salesforce.com [500]
XFH-Scheme: https://staging.bloom.salesforce.com [500]
XFH-Scheme: https://developer.salesforce.com [200]
XFH-Scheme: https://docs.developer.salesforce.com [421]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

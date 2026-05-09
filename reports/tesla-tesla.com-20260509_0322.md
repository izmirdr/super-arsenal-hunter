# 🎯 tesla — tesla.com
**Date:** Sat May  9 03:22:55 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 1386 |
| Live Hosts | 30 |
| URLs | 977 |
| Interesting Subs | 50 |
| IDOR Candidates | 0
0 |
| API Endpoints | 1 |
| JS Secrets | 0
0 |
| SSRF Candidates | 20 |
| Deep: SSRF Tests | 0 |
| Deep: Staging Hits | 0 |
| Deep: IDOR Suspects | 0 |
| Deep: Cache Checks | 6 |
| Deep: Origin Bypass | 7 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
*.sandbox-manager.courses.tesla.com
CitiApiEncProdv4.tesla.com
CitiApiEncProdv5.tesla.com
CitiApiEncSandboxv4.tesla.com
CitiApiPgpProdV6.tesla.com
CitiApiPgpProdV7.tesla.com
CitiApiSshProdV6.tesla.com
CitiApiSslProdV7.tesla.com
CitiApiSslProdv4.tesla.com
CitiApiSslProdv5.tesla.com
CitiApiSslSandboxv4.tesla.com
Payx-CitiAPI-Prod.tesla.com
account.apf-api.prd.vn.cloud.tesla.com
account.device-api.prd.na.vn.cloud.tesla.com
acme-sentry-4.eng.use1.vn.cloud.tesla.com
```

## Live Hosts
```
https://powerhub.energy.tesla.com [403] [Access Denied]
https://tesla.com [403] [Access Denied]
https://engage.tesla.com [200] [Engage Tesla]
https://engagetesla.com [302] [302 Found]
https://accounts.tesla.com [308]
https://akamai-apigateway-bender.tesla.com [301]
https://akamai-apigateway-charging-ownership.tesla.com [503] [Service Unavailable]
https://akamai-apigateway-captiveunderwriting.tesla.com [503] [Service Unavailable]
https://akamai-apigateway-einvoicing.tesla.com [301]
https://akamai-apigateway-finplateng-defi.tesla.com [403] [Access Denied]
```

## IDOR Candidates
```

```

## API Endpoints
```
https://www.tesla.com/api/tesla/header/megamenu/v1_2
```

## JS Secrets
```

```

## SSRF Candidates
```
https://www.tesla.com/?redirect=no
https://www.tesla.com/about/blog/11-questions-odyssey-pioneers-driver-luke-mcclure?redirect=no
https://www.tesla.com/about/press/press-mentions?page=12&redirect=no
https://www.tesla.com/about/press/releases/clone-tesla-motors-model-s-makes-its-asian-debut-hong-kong?page=3&redirect=no
https://www.tesla.com/about/press/releases/panasonic-enters-supply-agreement-tesla-motors-supply-automotivegrade-battery-c?redirect=no
https://www.tesla.com/about/press/releases/panasonic-presents-first-electric-vehicle-battery-tesla?redirect=no
https://www.tesla.com/about/press/releases/tesla-hires-apple-gap-veteran-revolutionize-car-buying-experience?redirect=no
https://www.tesla.com/about/press/releases/tesla-launches-battery-recycling-program-throughout-europe?redirect=no
https://www.tesla.com/about/press/releases/tesla-motors-announces-canadian-pricing-model-s?redirect=no
https://www.tesla.com/about/press/releases/tesla-motors-inizia-le-consegne-della-model-s-la-berlina-elettrica-premium-0?page=8&redirect=no
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
XFH-Scheme: https://powerhub.energy.tesla.com [302]
XFH-Scheme: https://tesla.com [403]
XFH-Scheme: https://engage.tesla.com [404]
CacheCand: https://engagetesla.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://engagetesla.com [302]
XFH-Scheme: https://accounts.tesla.com [308]
```

### CDN Bypass / Origin Discovery
```
CDN-BYPASS: engage.tesla.com → origin engage.tesla.io (47.240.5.85) [200 vs CDN 404]
CDN-BYPASS: accounts.tesla.com → origin accounts.tesla.io (47.240.5.85) [200 vs CDN 308]
CDN-BYPASS: akamai-apigateway-bender.tesla.com → origin akamai-apigateway-bender.tesla.io (47.240.5.85) [200 vs CDN 301]
CDN-BYPASS: akamai-apigateway-charging-ownership.tesla.com → origin akamai-apigateway-charging-ownership.tesla.io (47.240.5.85) [200 vs CDN 503]
CDN-BYPASS: akamai-apigateway-captiveunderwriting.tesla.com → origin akamai-apigateway-captiveunderwriting.tesla.io (47.240.5.85) [200 vs CDN 503]
CDN-BYPASS: akamai-apigateway-einvoicing.tesla.com → origin akamai-apigateway-einvoicing.tesla.io (47.240.5.85) [200 vs CDN 301]
CDN-BYPASS: akamai-apigateway-finplateng-defi.tesla.com → origin akamai-apigateway-finplateng-defi.tesla.io (47.240.5.85) [200 vs CDN 403]
```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

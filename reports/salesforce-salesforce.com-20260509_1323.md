# 🎯 salesforce — salesforce.com
**Date:** Sat May  9 13:23:56 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 69 |
| Live Hosts | 29 |
| URLs | 477 |
| Interesting Subs | 47 |
| IDOR Candidates | 0
0 |
| API Endpoints | 2 |
| JS Secrets | 0
0 |
| SSRF Candidates | 1 |
| Deep: SSRF Tests | 0 |
| Deep: Staging Hits | 0 |
| Deep: IDOR Suspects | 0 |
| Deep: Cache Checks | 6 |
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
admin.salesforce.com
admins.salesforce.com
ajna-api.salesforce.com
attestation.abuse-mx.salesforce.com
corporacionmultiinversiones--agenciadig.sandbox.my.salesforce.com
data-agility-787--dev.sandbox.my.salesforce.com
dcl1-dfw.ajna-api-dfw.salesforce.com
dcl1-ncg0-cdg3.ajna-api-cdg.salesforce.com
dcl1-ncg0-fra3.ajna-api-fra.salesforce.com
dcl1-ncg0-lhr3.ajna-api-lo2.salesforce.com
dcl10-ncg0-cdg3.ajna-api-cdg.salesforce.com
dcl10-ncg0-fra3.ajna-api-fra.salesforce.com
dcl11-ncg0-cdg3.ajna-api-cdg.salesforce.com
dcl11-ncg0-fra3.ajna-api-fra.salesforce.com
dcl12-ncg0-cdg3.ajna-api-cdg.salesforce.com
```

## Live Hosts
```
https://academic-alliance.salesforce.com [] [Fastly error: unknown domain academic-alliance.salesforce.com]
http://admins.salesforce.com [404] [UltraDNS Client Redirection Service]
https://accessibility.salesforce.com [302]
https://bcom.my.salesforce.com [200] [Login | Salesforce]
https://ai.salesforce.com [200]
https://customization-app-7729.my.salesforce.com [200] [Login | Salesforce]
https://alliedmachine.my.salesforce.com [200] [Login | Salesforce]
https://agentexchange.salesforce.com [200] [AgentExchange | Agents, apps, and tools for Salesforce & Slack]
https://attestation.abuse-mx.salesforce.com [200] [Salesforce Marketing Cloud - Compliance Attestation]
https://enterprise-java-5315.my.salesforce.com [200] [Login | Salesforce]
```

## IDOR Candidates
```

```

## API Endpoints
```
https://kv7kzm78.api.commercecloud.salesforce.com/product/products/v1/organizations/f_ecom_zzte_053/
https://kv7kzm78.api.commercecloud.salesforce.com/product/shopper-products/v1/organizations/f_ecom_z
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
XFH-Scheme: https://academic-alliance.salesforce.com [500]
XFH-Scheme: http://admins.salesforce.com [404]
CacheCand: https://accessibility.salesforce.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://accessibility.salesforce.com [302]
XFH-Scheme: https://bcom.my.salesforce.com [200]
XFH-Scheme: https://ai.salesforce.com [200]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

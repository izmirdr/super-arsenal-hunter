# 🎯 tesla — tesla.com
**Date:** Sun May 10 13:11:26 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 1355 |
| Live Hosts | 50 |
| URLs | 936 |
| Interesting Subs | 50 |
| IDOR Candidates | 0
0 |
| API Endpoints | 21 |
| JS Secrets | 0
0 |
| SSRF Candidates | 20 |
| Deep: SSRF Tests | 0 |
| Deep: Staging Hits | 0 |
| Deep: IDOR Suspects | 0 |
| Deep: Cache Checks | 7 |
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
CitiApiEncProdv5.tesla.com
CitiApiSslProdv5.tesla.com
account.apf-api.prd.vn.cloud.tesla.com
account.device-api.prd.na.vn.cloud.tesla.com
acme-sentry-4.eng.use1.vn.cloud.tesla.com
acme-sentry-4a.eng.use1.vn.cloud.tesla.com
admin.apigateway-logging.tesla.com
admin.digitalassets.tesla.com
admin.dpuas-prd.usw.vn.cloud.tesla.com
admin.eu.vn.cloud.tesla.com
ads.akamai-apigateway-vfx.tesla.com
ai-api-stg.tesla.com
ai-api-uat.tesla.com
ai-api.tesla.com
akamai-apigateway-automation.tesla.com
```

## Live Hosts
```
https://akamai-apigateway-bender.tesla.com [301]
https://akamai-apigateway-captiveunderwriting.tesla.com [503] [Service Unavailable]
https://akamai-apigateway-charging-ownership.tesla.com [503] [Service Unavailable]
https://engagetesla.com [302] [302 Found]
https://akamai-apigateway-deliveryopsvitu.tesla.com [503] [Service Unavailable]
https://akamai-apigateway-deliveryopsapi1.tesla.com [503] [Service Unavailable]
https://akamai-apigateway-deliveryopsapi.tesla.com [503] [Service Unavailable]
https://akamai-apigateway-automation.tesla.com [503] [Service Unavailable]
https://accounts.tesla.com [308]
https://akamai-apigateway-ehs-stg.tesla.com [403] [Access Denied]
```

## IDOR Candidates
```

```

## API Endpoints
```
http://auth.tesla.com/oauth2/v3/authorize
https://apigateway-charging-bff.tesla.com/api/graphql
https://auth.tesla.com/de_at/oauth2/v1/authorize
https://auth.tesla.com/de_de/oauth2/v1/authorize
https://auth.tesla.com/no_no/oauth2/v1/authorize
https://auth.tesla.com/oauth2/v1/authorize&response_type=code&locale=en-US&code=NA_568a415732070c8a3a1716ce427c71be033508f10be7d494bd8d8e235b0b&state=Mj1r488f&issuer=https:/auth.tesla.com/oauth2/v3
https://auth.tesla.com/oauth2/v3/authorize
https://auth.tesla.com/oauth2/v3/authorizej5gK
https://auth.tesla.com/oauth2/v3/tokenTESLA_TOKENS_PATHsrc
https://auth.tesla.com/oauth2/v3/tokensrc
```

## JS Secrets
```

```

## SSRF Candidates
```
https://www.tesla.com/?error=login_required&state=ZG&error_description=AADSTS50058%3A%20A%20silent%20sign-in%20request%20was%20sent%20but%20no%20user%20is%20signed%20in.%20The%20cookies%20used%20to%20represent%20the%20user%27s%20session%20were%20not%20sent%20in%20the%20request%20to%20Azure%20AD.%20This%20can%20happen%20if%20the%20user%20is%20using%20Internet%20Explorer%20or%20Edge%2C%20and%20the%20web%20app%20sending%20the%20silent%20sign-in%20request%20is%20in%20different%20IE%20security%20zone%20than%20the%20Azure%20AD%20endpoint%20(login.microsoftonline.com).%20Trace%20ID%3A%2053bcc298-60ff-4373-b1bb-a85bdf034600%20Correlation%20ID%3A%202c054ed5-2d2e-4809-998c-cd8a4cd9f61d%20Timestamp%3A%202026-05-01%2002%3A14%3A32Z&error_uri=https%3A%2F%2Flogin.microsoftonline.com%2Ferror%3Fcode%3D50058
https://www.tesla.com/?redirect=no
https://www.tesla.com/about/blog/11-questions-odyssey-pioneers-driver-luke-mcclure?redirect=no
https://www.tesla.com/about/press/press-mentions?page=12&redirect=no
https://www.tesla.com/about/press/releases/clone-tesla-motors-model-s-makes-its-asian-debut-hong-kong?page=3&redirect=no
https://www.tesla.com/about/press/releases/panasonic-enters-supply-agreement-tesla-motors-supply-automotivegrade-battery-c?redirect=no
https://www.tesla.com/about/press/releases/panasonic-presents-first-electric-vehicle-battery-tesla?redirect=no
https://www.tesla.com/about/press/releases/tesla-hires-apple-gap-veteran-revolutionize-car-buying-experience?redirect=no
https://www.tesla.com/about/press/releases/tesla-launches-battery-recycling-program-throughout-europe?redirect=no
https://www.tesla.com/about/press/releases/tesla-motors-announces-canadian-pricing-model-s?redirect=no
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
CacheCand: https://akamai-apigateway-bender.tesla.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://akamai-apigateway-bender.tesla.com [301]
XFH-Scheme: https://akamai-apigateway-captiveunderwriting.tesla.com [503]
XFH-Scheme: https://akamai-apigateway-charging-ownership.tesla.com [503]
CacheCand: https://engagetesla.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://engagetesla.com [302]
XFH-Scheme: https://akamai-apigateway-deliveryopsvitu.tesla.com [503]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

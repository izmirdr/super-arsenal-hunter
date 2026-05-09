# 🎯 Proximus — proximus.be
**Date:** Sat May  9 09:59:27 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | — |
| Live Hosts | 20 |
| URLs | — |
| Interesting Subs | 50 |
| IDOR Candidates | 0 |
| API Endpoints | 0 |
| JS Secrets | 0 |
| SSRF Candidates | 0 |
| Deep: SSRF Tests | 0 |
| Deep: Staging Hits | 0 |
| Deep: IDOR Suspects | 0 |
| Deep: Cache Checks | 0 |
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
a2a-dev.proximus.be
a2a-staging.proximus.be
aan-uat.proximus.be
admit-uat.proximus.be
agf-uat.proximus.be
api-dev.proximus.be
api-iot.proximus.be
api-itt.proximus.be
api-psu.proximus.be
api-staging.proximus.be
api-sys.proximus.be
api-trn.proximus.be
api-uat.proximus.be
api.beopen.proximus.be
api.guestwifi.proximus.be
api.proximus.be
app-belfius-banking-dev.cockpit.proximus.be
app-belfius-banking-uat.cockpit.proximus.be
app-belfius-banking-uat2.cockpit.proximus.be
b2b-dev.proximus.be
```

## Live Hosts
```
https://adhoctstnc1.proximus.be [401]
https://api-iot.proximus.be [404]
https://app-belfius-banking-dr.cockpit.proximus.be [302]
https://adhoctstnc3.proximus.be [401]
https://adhoc.proximus.be [401]
https://api.guestwifi.proximus.be [200] [WiFi Login]
https://api.proximus.be [200] [Proximus API Gateway]
https://api-uat.proximus.be [200] [Proximus API Gateway]
https://b2b-dev.proximus.be [200] [RHEL Test Page]
https://b2b.proximus.be [200] [RHEL Test Page]
```

## 🔥 Deep Exploitation (Verified)

### Manual Verification
```
✅ api.proximus.be → Proximus API Gateway (public welcome page)
✅ api-uat.proximus.be → UAT API Gateway (public welcome page)
✅ api.guestwifi.proximus.be → WiFi login portal
✅ b2b-dev.proximus.be → Default RHEL test page (misconfigured)
⚠️ No API endpoints accessible without auth
```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

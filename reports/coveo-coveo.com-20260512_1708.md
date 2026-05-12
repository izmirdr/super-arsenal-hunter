# 🎯 coveo — coveo.com
**Date:** Tue May 12 17:08:01 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 1149 |
| Live Hosts | 30 |
| URLs | 976 |
| Interesting Subs | 50 |
| IDOR Candidates | 0
0 |
| API Endpoints | 30 |
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
101dev.coveo.com
101staging.coveo.com
account.demoadidas51c4m0wi.org.coveo.com
admin-ui.coveo.com
admin.analytics-eu.cloud.coveo.com
admin.analytics.org.coveo.com
admin.athenahealthprod.analytics.orghipaa.coveo.com
admin.cityofnewyorkproduction1oub1837a.analytics.org.coveo.com
admin.cloud.coveo.com
admin.commonwealthofpennsylvaniaproductiono8jd9ckm.org.coveo.com
admin.concury9vvkaz3.org.coveo.com
admin.daikinappliedproductioncszg6439.analytics.org.coveo.com
admin.fanniemae9glu2r77.org.coveo.com
admin.fleetprideproductionmdo2j87b.org.coveo.com
admin.intelcorporationproductione78n25s6.org.coveo.com
```

## Live Hosts
```
https://academy.coveo.com [302]
https://101.coveo.com [302]
https://agilenttechnologiesincproduction1gdm08hx7.org.coveo.com [302]
https://analytics.cloud.coveo.com [302]
https://adiglobalcorporationproductioni0dbih7a.org.coveo.com [302]
https://adiglobalcorporationproductioni0dbih7a.analytics.org.coveo.com [302]
https://analytics-ca.cloud.coveo.com [302]
https://ai.coveo.com [204]
https://answers.coveo.com [301]
https://answer.coveo.com [301]
```

## IDOR Candidates
```

```

## API Endpoints
```
https://aarpu11lxv0p.org.coveo.com/rest/search/v2/querySuggest
https://ai.coveo.com/api/mailings/opened/PMRGSZBCHI2DEOJWGI2SYITPOJTSEORCGJQTSMBWHEYDOLJZMFRTELJUMUYDKLLCMQZTGLJWHBSWCZBVG42TQZTBGARCYITWMVZHG2LPNYRDUIRUEIWCE43JM4RDUITHKNHWWQJWOJFEMWLOJVTGYZTIJIYVU23PGV3W4S3HHFMTOWCIJU4FOSJQI44EE2SHPFCT2IT5.gif
https://ai.coveo.com/api/mailings/unsubscribe/PMRGSZBCHI2DCMZWHA4SYITPOJTSEORCGJQTSMBWHEYDOLJZMFRTELJUMUYDKLLCMQZTGLJWHBSWCZBVG42TQZTBGARCYITWMVZHG2LPNYRDUIRUEIWCE43JM4RDUISJJY4VOR32MFWWK52GIFZXG32CFVIDGT3UJ5MFAZCRKVETQOKOLAZTQVSJKJLWS2DNMFAT2IT5
https://ai.coveo.com/api/mailings/unsubscribe/PMRGSZBCHI2DCNBTGAYCYITPOJTSEORCGJQTSMBWHEYDOLJZMFRTELJUMUYDKLLCMQZTGLJWHBSWCZBVG42TQZTBGARCYITWMVZHG2LPNYRDUIRUEIWCE43JM4RDUISDIM4FCV3XG53DALKCKFGU22KHGZNG62DOOA2FOVSNKU4U6VKDJNZTAQRWJZGHC6SOJJRT2IT5
https://ai.coveo.com/api/mailings/unsubscribe/PMRGSZBCHI2DENBZHA4SYITPOJTSEORCGJQTSMBWHEYDOLJZMFRTELJUMUYDKLLCMQZTGLJWHBSWCZBVG42TQZTBGARCYITWMVZHG2LPNYRDUIRUEIWCE43JM4RDUITPJNQVGQT2KJ2EINSBKNGFSN2YIRFWSSK2GJIFORCQNNYXI52IIRTTSZRXIRWU65CQORZT2IT5
https://ai.coveo.com/api/mailings/unsubscribe/PMRGSZBCHI2DEOJWGI2SYITPOJTSEORCGJQTSMBWHEYDOLJZMFRTELJUMUYDKLLCMQZTGLJWHBSWCZBVG42TQZTBGARCYITWMVZHG2LPNYRDUIRUEIWCE43JM4RDUITMHFRHUTZWNJCXMWLJL5DW4MCIIVBTS5JUKBEW4WBNI5EDESJWJ5AXETKPJUZGQTDDJAYD2IT5
https://cdn.coveo.com/image/authenticated/s--OJaYuntC--/d_placeholder.png,h_858,w_1524/f_auto/v1/web/web01/en/library/images/r360/agentic_ai_masterclass_aws/ccs-14775_web_masterclass_aws_thumb_og_1
https://connectwiseproduction36o5x1p5.org.coveo.com/rest/search
https://dropboxproductionpmlw0l3v.analytics.org.coveo.com/rest/ua/v15/analytics/collect
https://dropboxproductionpmlw0l3v.org.coveo.com/rest/search
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
CacheCand: https://academy.coveo.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://academy.coveo.com [302]
CacheCand: https://101.coveo.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://101.coveo.com [302]
CacheCand: https://agilenttechnologiesincproduction1gdm08hx7.org.coveo.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://agilenttechnologiesincproduction1gdm08hx7.org.coveo.com [302]
CacheCand: https://analytics.cloud.coveo.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://analytics.cloud.coveo.com [302]
CacheCand: https://adiglobalcorporationproductioni0dbih7a.org.coveo.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://adiglobalcorporationproductioni0dbih7a.org.coveo.com [302]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

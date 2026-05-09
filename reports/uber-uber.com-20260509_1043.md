# 🎯 uber — uber.com
**Date:** Sat May  9 10:43:09 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 70 |
| Live Hosts | 66 |
| URLs | 549 |
| Interesting Subs | 10 |
| IDOR Candidates | 0
0 |
| API Endpoints | 13 |
| JS Secrets | 0
0 |
| SSRF Candidates | 20 |
| Deep: SSRF Tests | 0 |
| Deep: Staging Hits | 0 |
| Deep: IDOR Suspects | 0 |
| Deep: Cache Checks | 9 |
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
api-asterisk.uber.com
api.uber.com
auth.uber.com
backup.uber.com
biz-stage.uber.com
cisionone-email.uber.com
developer.uber.com
email.mgm.uber.com
email.mgt.uber.com
tdottest1.uber.com
```

## Live Hosts
```
https://api.uber.com [301] [301 Moved Permanently]
https://cn-dc1.uber.com [403]
https://api-asterisk.uber.com [301]
https://business.uber.com [301] [301 Moved Permanently]
https://central.uber.com [301] [301 Moved Permanently]
http://cn-ecg.cfe.uber.com [301]
https://cloudflare-weighted.uber.com [404]
https://beacon.uber.com [301]
https://auth.uber.com [301] [301 Moved Permanently]
https://cn-dca1.uber.com [403]
```

## IDOR Candidates
```

```

## API Endpoints
```
https://auth.uber.com/v2/?breeze_init_req_id=09000895-eb2e-4224-ad66-6266f0944a06&breeze_local_zone=dca22&next_url=https%3A%2F%2Fbiz.uber.com%2Fconfirm%2F48UUZTCS8%3Faction%3Dredeem-employee-invite%26confirmation_token%3D48UUZTCS8%26decentralized%3Dtrue%26logo_image_url%3Dhttps%253A%252F%252Ftb-static.uber.com%252Fprod%252Frenaissance%252Fcdn%252ForganizationLogos%252Fb230ce53-eba1-400b-8d56-b13153d59b31.jpeg%253Fv%253D1710442684591%26organization_name%3DSoftchoice%26show_pp%3Dtrue%26show_tier_disclaimer%3Dfalse%26signature%3D324e993b3dc16bd6a10ea2733e172a89ee066fc2%26signature_expiry%3D1777924821%26uuid%3Df07d6197-a6bc-4745-a844-a42800a2365d&sm_flow_id=u47nCFzk&state=7oOs6CFqBYPYfQxgISKs8ceuoaYQsWSePbfxJWV95D4%3D
https://auth.uber.com/v2/?breeze_init_req_id=0e7bcd9c-319e-43ec-8ce5-00fb173f5537&breeze_local_zone=dca52&next_url=https%3A%2F%2Friders.uber.com%2Ftrips%2Fbdbb03ba-f580-421c-b728-00d556f09530%2Freceipt%3FcontentType%3DPDF&sm_flow_id=wj5oz2uJ&state=Ix8BQG-bf8Pdx7_qmKN4jX7ufcH8xIDXFFDlij8qNgY%3D
https://auth.uber.com/v2/?breeze_init_req_id=138fe4cf-7e14-4b7c-b1d1-d2dc1370bf37&breeze_local_zone=dca23&next_url=https%3A%2F%2Faccount.uber.com%2Faccount&sm_flow_id=oAeVoRw-&state=UiOlPHV5w8PnjI_tZb9_doiLimsZMidaaetpyCgwL5I%3D
https://auth.uber.com/v2/?breeze_init_req_id=225647a3-2afa-46c2-b144-9160fdf60f8f&breeze_local_zone=dca24&next_url=https%3A%2F%2Friders.uber.com%2Ftrips%2Fbdbb03ba-f580-421c-b728-00d556f09530&sm_flow_id=4igRcFzm&state=THbyujBydnyh9gWNGb-l5ZKvx6M64g5GWoE8bCnS6XE%3D
https://auth.uber.com/v2/?breeze_init_req_id=413dcdc2-5eed-425c-90a5-d6cea556387d&breeze_local_zone=phx52&next_url=https%3A%2F%2Fops.uberfreight.com%2Fc%2Fload%2F2492761929&sm_flow_id=Rv6q158u&state=1i1U0zFxF8a3jfmC3_oI4S-I5Ojen3tOa9Kf_cE8GKA%3D
https://auth.uber.com/v2/?breeze_init_req_id=5232e4b6-b611-40c6-9119-c217f41391ff&breeze_local_zone=dca52&next_url=https%3A%2F%2Faccount.uber.com%2Faccount&sm_flow_id=y4Kk33Nr&state=VqPDyslfIVMLoMgAZm_LD7Qm5D4K30TEK9K8YntvdwY%3D
https://auth.uber.com/v2/?breeze_init_req_id=66909b52-9861-4468-a1a9-d1f28402bdc0&breeze_local_zone=dca22&next_url=https%3A%2F%2Friders.uber.com%2Ftrips%2Ff88b68be-99a8-483e-89fa-b04932bd2e7e%2Freceipt%3F_csid%3DhFegKLgHG-hRt2xWF6_OVg%26contentType%3DPDF%26effect%3D%26sm_flow_id%3DaSjhZxZ8%26state%3DRw9aGRrfgbSDO-PsUktwyab_EdD5kwnmfycQygrmau4%253D&sm_flow_id=tw7eTp6k&state=av3OlZNvY4fVgI9yvniZadh9OormGgIBMacI8wWMGvE%3D
https://auth.uber.com/v2/?breeze_init_req_id=82a8ddf5-318a-4128-b098-377602cb8425&breeze_local_zone=dca52&next_url=https%3A%2F%2Friders.uber.com%2Ftrips&sm_flow_id=cYX5m5An&state=SgH55E10DQBbF-dymwJET0tM-_gMs9gY2YXxJE3vH2s%3D
https://auth.uber.com/v2/?breeze_init_req_id=840a15a2-49e4-49b1-b67d-31354b93551a&breeze_local_zone=dca24&next_url=https%3A%2F%2Fwww.ubereats.com%2Flogin-redirect%2F%3Fredirect%3D%252Forders%253Fmod%253DorderReceipt%2526modctx%253D2bc7b806-c9b0-4573-a914-6ab504ff30fc%2526ps%253D1&sm_flow_id=w3OPEDuE&state=bZpgyJrEXa9laedsO8cnIKsMR66X8IQSezBiCIMpp6g%3D&x-uber-did=a1f47da2-ab8a-4e05-aaac-fedce1a141c8
https://auth.uber.com/v2/?breeze_init_req_id=8617d4ba-77cf-40ac-b759-9eac5126746e&breeze_local_zone=dca52&next_url=https%3A%2F%2Friders.uber.com%2Ftrips&sm_flow_id=ya3fUBDo&state=TxWhRxgirSmHoz8SdNqV9sOH6Xj0SslJWejXuE8z5UQ%3D
```

## JS Secrets
```

```

## SSRF Candidates
```
https://auth.uber.com/v2/?breeze_init_req_id=09000895-eb2e-4224-ad66-6266f0944a06&breeze_local_zone=dca22&next_url=https%3A%2F%2Fbiz.uber.com%2Fconfirm%2F48UUZTCS8%3Faction%3Dredeem-employee-invite%26confirmation_token%3D48UUZTCS8%26decentralized%3Dtrue%26logo_image_url%3Dhttps%253A%252F%252Ftb-static.uber.com%252Fprod%252Frenaissance%252Fcdn%252ForganizationLogos%252Fb230ce53-eba1-400b-8d56-b13153d59b31.jpeg%253Fv%253D1710442684591%26organization_name%3DSoftchoice%26show_pp%3Dtrue%26show_tier_disclaimer%3Dfalse%26signature%3D324e993b3dc16bd6a10ea2733e172a89ee066fc2%26signature_expiry%3D1777924821%26uuid%3Df07d6197-a6bc-4745-a844-a42800a2365d&sm_flow_id=u47nCFzk&state=7oOs6CFqBYPYfQxgISKs8ceuoaYQsWSePbfxJWV95D4%3D
https://auth.uber.com/v2/?breeze_init_req_id=0e7bcd9c-319e-43ec-8ce5-00fb173f5537&breeze_local_zone=dca52&next_url=https%3A%2F%2Friders.uber.com%2Ftrips%2Fbdbb03ba-f580-421c-b728-00d556f09530%2Freceipt%3FcontentType%3DPDF&sm_flow_id=wj5oz2uJ&state=Ix8BQG-bf8Pdx7_qmKN4jX7ufcH8xIDXFFDlij8qNgY%3D
https://auth.uber.com/v2/?breeze_init_req_id=138fe4cf-7e14-4b7c-b1d1-d2dc1370bf37&breeze_local_zone=dca23&next_url=https%3A%2F%2Faccount.uber.com%2Faccount&sm_flow_id=oAeVoRw-&state=UiOlPHV5w8PnjI_tZb9_doiLimsZMidaaetpyCgwL5I%3D
https://auth.uber.com/v2/?breeze_init_req_id=225647a3-2afa-46c2-b144-9160fdf60f8f&breeze_local_zone=dca24&next_url=https%3A%2F%2Friders.uber.com%2Ftrips%2Fbdbb03ba-f580-421c-b728-00d556f09530&sm_flow_id=4igRcFzm&state=THbyujBydnyh9gWNGb-l5ZKvx6M64g5GWoE8bCnS6XE%3D
https://auth.uber.com/v2/?breeze_init_req_id=413dcdc2-5eed-425c-90a5-d6cea556387d&breeze_local_zone=phx52&next_url=https%3A%2F%2Fops.uberfreight.com%2Fc%2Fload%2F2492761929&sm_flow_id=Rv6q158u&state=1i1U0zFxF8a3jfmC3_oI4S-I5Ojen3tOa9Kf_cE8GKA%3D
https://auth.uber.com/v2/?breeze_init_req_id=5232e4b6-b611-40c6-9119-c217f41391ff&breeze_local_zone=dca52&next_url=https%3A%2F%2Faccount.uber.com%2Faccount&sm_flow_id=y4Kk33Nr&state=VqPDyslfIVMLoMgAZm_LD7Qm5D4K30TEK9K8YntvdwY%3D
https://auth.uber.com/v2/?breeze_init_req_id=66909b52-9861-4468-a1a9-d1f28402bdc0&breeze_local_zone=dca22&next_url=https%3A%2F%2Friders.uber.com%2Ftrips%2Ff88b68be-99a8-483e-89fa-b04932bd2e7e%2Freceipt%3F_csid%3DhFegKLgHG-hRt2xWF6_OVg%26contentType%3DPDF%26effect%3D%26sm_flow_id%3DaSjhZxZ8%26state%3DRw9aGRrfgbSDO-PsUktwyab_EdD5kwnmfycQygrmau4%253D&sm_flow_id=tw7eTp6k&state=av3OlZNvY4fVgI9yvniZadh9OormGgIBMacI8wWMGvE%3D
https://auth.uber.com/v2/?breeze_init_req_id=82a8ddf5-318a-4128-b098-377602cb8425&breeze_local_zone=dca52&next_url=https%3A%2F%2Friders.uber.com%2Ftrips&sm_flow_id=cYX5m5An&state=SgH55E10DQBbF-dymwJET0tM-_gMs9gY2YXxJE3vH2s%3D
https://auth.uber.com/v2/?breeze_init_req_id=840a15a2-49e4-49b1-b67d-31354b93551a&breeze_local_zone=dca24&next_url=https%3A%2F%2Fwww.ubereats.com%2Flogin-redirect%2F%3Fredirect%3D%252Forders%253Fmod%253DorderReceipt%2526modctx%253D2bc7b806-c9b0-4573-a914-6ab504ff30fc%2526ps%253D1&sm_flow_id=w3OPEDuE&state=bZpgyJrEXa9laedsO8cnIKsMR66X8IQSezBiCIMpp6g%3D&x-uber-did=a1f47da2-ab8a-4e05-aaac-fedce1a141c8
https://auth.uber.com/v2/?breeze_init_req_id=8617d4ba-77cf-40ac-b759-9eac5126746e&breeze_local_zone=dca52&next_url=https%3A%2F%2Friders.uber.com%2Ftrips&sm_flow_id=ya3fUBDo&state=TxWhRxgirSmHoz8SdNqV9sOH6Xj0SslJWejXuE8z5UQ%3D
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
CacheCand: https://api.uber.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://api.uber.com [301]
XFH-Scheme: https://cn-dc1.uber.com [403]
CacheCand: https://api-asterisk.uber.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://api-asterisk.uber.com [301]
CacheCand: https://business.uber.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://business.uber.com [301]
CacheCand: https://central.uber.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://central.uber.com [301]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

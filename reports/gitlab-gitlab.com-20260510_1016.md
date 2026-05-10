# 🎯 gitlab — gitlab.com
**Date:** Sun May 10 10:16:39 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 646 |
| Live Hosts | 8 |
| URLs | 934 |
| Interesting Subs | 50 |
| IDOR Candidates | 9 |
| API Endpoints | 9 |
| JS Secrets | 0
0 |
| SSRF Candidates | 10 |
| Deep: SSRF Tests | 0 |
| Deep: Staging Hits | 0 |
| Deep: IDOR Suspects | 0 |
| Deep: Cache Checks | 7 |
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
*.about-src.gitlab.com
*.about.gitlab.com
*.design.gitlab.com
*.gitlab.com
*.gprd.gitlab.com
*.gstg.gitlab.com
*.observe.gitlab.com
*.observe.staging.gitlab.com
*.pre.gitlab.com
*.single.gitlab.com
*.staging-ref.gitlab.com
*.staging.gitlab.com
2670515-review-enable-aut-a96d5t.cust-staging.gitlab.com
4456656-review-1107-add-e-53243j.design-staging.gitlab.com
4456656-review-1179-toggl-8ctzom.design-staging.gitlab.com
```

## Live Hosts
```
https://observe.gitlab.com [404]
https://about.gitlab.com [200] [Finally, AI for the entire software lifecycle.]
https://pre.gitlab.com [302]
https://gitlab.com [301]
https://observe.staging.gitlab.com [404]
https://staging-ref.gitlab.com [302]
https://staging.gitlab.com [301]
https://design.gitlab.com [200] [Pajamas Design System]
```

## IDOR Candidates
```
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2FRich-Harris%2Fbuble%2Fissues%2F171&user_id=239334
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Fanarcat%2Fwallabako%2Fissues%2F21&user_id=71118
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Fgitlab-org%2Fgitlab-ce%2Fissues%2F19232&user_id=554089
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Fgitlab-org%2Fgitlab-ce%2Fissues%2F28908&user_id=424775
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Fgitlab-org%2Fgitlab-ee%2Fissues%2F4743&user_id=1273957
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Fgnachman%2Fiterm2%2Fissues%2F6637&user_id=2201962
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Foath-toolkit%2Foath-toolkit%2Fmerge_requests%2F6&user_id=284862
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Frobigalia%2Fmeta%2Fissues%2F17&user_id=247834
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Fxonotic%2Fnetradiant%2Fissues%2F93&user_id=210963
```

## API Endpoints
```
https://docs.gitlab.com/api/scim/
https://docs.gitlab.com/ee/api/graphql/
https://enable.gitlab.com/api/mailings/opened/PMRGSZBCHI4TSOJQGMYSYITPOJTSEORCGY3DAM3FMVRDMLJYMZRGILJUMNRGILLCGI2WILJRGZTGKOJXG44TSZRUMERCYITWMVZHG2LPNYRDUIRUEIWCE43JM4RDUITMGFXFO3JQMU2WWNJVMVWFU3LBMU2U6YLCGZMFCR2FOFRXANDTORUTSX27KVMTKTDTOBKT2IT5.gif
https://enable.gitlab.com/api/mailings/unsubscribe/PMRGSZBCHI4TSOJQGMYSYITPOJTSEORCGY3DAM3FMVRDMLJYMZRGILJUMNRGILLCGI2WILJRGZTGKOJXG44TSZRUMERCYITWMVZHG2LPNYRDUIRUEIWCE43JM4RDUIT2G43HOSRQK5LGKOCRJ5CTK42GGBFG6U2OKQ3VKV3WG43FAOBUJNKXOOC2N44XM6CEKBTT2IT5
https://gitlab.com/api/v4/
https://gitlab.com/api/v4/groups/122023679/variables
https://gitlab.com/api/v4/projects/gitlab-org/gitlab-runner
https://gitlab.com/api/v4/projects/isi/dev/binah/surgical-guidance-docs/merge_requests/48
https://gitlab.com/api/v4/projects/moxa/sw/f2e/networking/f2e-networking/repository/files/
```

## JS Secrets
```

```

## SSRF Candidates
```
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2FRich-Harris%2Fbuble%2Fissues%2F171&user_id=239334
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Fanarcat%2Fwallabako%2Fissues%2F21&user_id=71118
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Fgitlab-org%2Fgitlab-ce%2Fissues%2F19232&user_id=554089
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Fgitlab-org%2Fgitlab-ce%2Fissues%2F28908&user_id=424775
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Fgitlab-org%2Fgitlab-ee%2Fissues%2F4743&user_id=1273957
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Fgnachman%2Fiterm2%2Fissues%2F6637&user_id=2201962
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Foath-toolkit%2Foath-toolkit%2Fmerge_requests%2F6&user_id=284862
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Frobigalia%2Fmeta%2Fissues%2F17&user_id=247834
https://gitlab.com/abuse_reports/new?ref_url=https%3A%2F%2Fgitlab.com%2Fxonotic%2Fnetradiant%2Fissues%2F93&user_id=210963
https://gitlab.com/groups/latamairlines/-/saml/sso?redirect=latamairlines&token=J39-Hyn-
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
XFH-Scheme: https://observe.gitlab.com [404]
XFH-Scheme: https://about.gitlab.com [200]
CacheCand: https://pre.gitlab.com responds 302 to X-Forwarded-Host: evil.com
XFH-Scheme: https://pre.gitlab.com [302]
CacheCand: https://gitlab.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://gitlab.com [301]
XFH-Scheme: https://observe.staging.gitlab.com [404]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

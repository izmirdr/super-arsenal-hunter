# SUPER-ARSENAL HUNTER — GitHub Actions

Bug bounty autonomous hunter running on GitHub Actions free tier (unlimited minutes for public repos).

## How it works

Every 3 hours, the workflow:
1. Picks a random target from 14 high-bounty programs
2. Passive recon: subfinder + crt.sh + assetfinder → subdomains
3. Live detection: httpx → active hosts
4. URL collection: gau + waybackurls + katana
5. Vulnerability scanning: IDOR, API, JS secrets (jsluice), SSRF, Nuclei
6. Generates report → saved as artifact + committed to repo

## Programs Tracked (39)

aol, atlassian, cisco, cloudflare, coinbase, coveo, docker, dropbox, expressvpn, fastly,
github, gitlab, indeed, linkedin, mastercard, mozilla, netflix, okta, orange, ovhcloud,
paypal, proximus, reddit, salesforce, shopify, slack, snapchat, spotify, tesla, tiktok,
twilio, twitter, uber, verizonmedia, wordpress, wordpress.org, x.com, yahoo, yelp

## Manual Trigger

```
gh workflow run hunt.yml -f domain=example.com -f program=Example
```

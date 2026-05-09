# 🎯 spotify — spotify.com
**Date:** Sat May  9 18:58:38 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 52 |
| Live Hosts | 40 |
| URLs | 997 |
| Interesting Subs | 17 |
| IDOR Candidates | 0
0 |
| API Endpoints | 23 |
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
adeventtracker.spotify.com
adgen-dev.spotify.com
admin.adanalytics.spotify.com
api-partner.spotify.com
api-tv.spotify.com
api.adanalytics.spotify.com
api.spotify.com
artists-testing.spotify.com
auth-callback.spotify.com
authors.spotify.com
backstage-marketing.spotify.com
backstage.spotify.com
beta-developer.spotify.com
beta.spotify.com
clicks.hello.authors.spotify.com
```

## Live Hosts
```
https://beta.spotify.com [421]
https://holidayswithspotify.com [301]
https://api-partner.spotify.com [204]
https://admin.adanalytics.spotify.com [200]
https://adsmanager.spotify.com [301]
https://accounts.spotify.com [307]
https://beta-developer.spotify.com [200] [Home | Spotify for Developers]
https://blog.spotify.com [421]
https://open.spotify.com [200] [Spotify – Web Player]
https://adstudio-help.spotify.com [404]
```

## IDOR Candidates
```

```

## API Endpoints
```
https://accounts.spotify.com/oauth2/v2/auth
https://api.spotify.com/v1/L
https://api.spotify.com/v1/me
https://api.spotify.com/v1/me/albums
https://api.spotify.com/v1/me/episodes
https://api.spotify.com/v1/me/player
https://api.spotify.com/v1/me/player/currently
https://api.spotify.com/v1/me/player/queue
https://api.spotify.com/v1/me/player/recently
https://api.spotify.com/v1/me/playlists
```

## JS Secrets
```

```

## SSRF Candidates
```
https://www.spotify.com/ar/signup/?los_url=https%3A//open.spotify.com/album/7Dj0aaKI4RpehMPqOu56mW&los_uri=spotify%3Aalbum%3A7Dj0aaKI4RpehMPqOu56mW&los_title=Beach+House+3&los_media=https%3A//i.scdn.co/image/f71baf14611a39b3cbd652c028b4aa4210016071&los_type=track
https://www.spotify.com/ar/signup/?los_url=https%3A//open.spotify.com/album/7kKKiNCsiTzO3grViZpVld&los_uri=spotify%3Aalbum%3A7kKKiNCsiTzO3grViZpVld&los_title=Por+Favor&los_media=https%3A//i.scdn.co/image/59190b22e2c16b5b88daaa035543f9a0e98db0a3&los_type=track
https://www.spotify.com/ar/signup/?los_url=https%3A//open.spotify.com/show/0ofXAdFIQQRsCYj9754UFx&los_uri=spotify%3Ashow%3A0ofXAdFIQQRsCYj9754UFx&los_title=Stuff+You+Should+Know&los_media=https%3A//i.scdn.co/image/26716dfbadc80867447fef638052050947c16b85&los_type=show
https://www.spotify.com/ar/signup/?los_url=https%3A//open.spotify.com/show/5FqJcvfGMLledCODGqV4J9&los_uri=spotify%3Ashow%3A5FqJcvfGMLledCODGqV4J9&los_title=Up+and+Vanished&los_media=https%3A//i.scdn.co/image/7d8ca85ab892da241fd19a305f30cfb82aefe6af&los_type=show
https://www.spotify.com/ar/signup/?los_url=https%3A//open.spotify.com/show/6xqETOvGnSQHH0xdLtgcXU&los_uri=spotify%3Ashow%3A6xqETOvGnSQHH0xdLtgcXU&los_title=Myths+and+Legends&los_media=https%3A//i.scdn.co/image/ee2ae574c54a95539b450c6b53c6e323815d2f34&los_type=show
https://www.spotify.com/ar/signup/?los_url=https%3A//open.spotify.com/track/2SmgFAhQkQCQPyBiBxR6Te&los_uri=spotify%3Atrack%3A2SmgFAhQkQCQPyBiBxR6Te&los_title=Criminal&los_media=https%3A//i.scdn.co/image/9623da68977e7e0d5f926be091ac5f7f36d983a4&los_type=track
https://www.spotify.com/ar/signup/?los_url=https%3A//open.spotify.com/user/spotify/playlist/37i9dQZF1DXbbu94YBG7Ye&los_uri=spotify%3Auser%3Aspotify%3Aplaylist%3A37i9dQZF1DXbbu94YBG7Ye&los_title=%C3%89xitos+Argentina&los_media=https%3A//i.scdn.co/image/bf5c486eb382e7e255295f32c157f1ff88e78130&los_type=show
https://www.spotify.com/au/signup/?los_url=https%3A//open.spotify.com/album/3EwfQtjvyRAXsPWAKO5FDP&los_uri=spotify%3Aalbum%3A3EwfQtjvyRAXsPWAKO5FDP&los_title=Pacific+Daydream&los_media=https%3A//i.scdn.co/image/0074e12e5155e33f46285b7ba5ed5f0b297d94e0&los_type=track
https://www.spotify.com/au/signup/?los_url=https%3A//open.spotify.com/album/55IoPTWDaFLWGhxR7E4YSH&los_uri=spotify%3Aalbum%3A55IoPTWDaFLWGhxR7E4YSH&los_title=MotorSport&los_media=https%3A//i.scdn.co/image/5ecb68504b9b260f7b123b60dd51ad0b557d0b89&los_type=track
https://www.spotify.com/au/signup/?los_url=https%3A//open.spotify.com/album/5gQZvWM1o8NkQndueJtZcP&los_uri=spotify%3Aalbum%3A5gQZvWM1o8NkQndueJtZcP&los_title=Wolves&los_media=https%3A//i.scdn.co/image/e60e143c955ab6c8aeda4edf934c94e5b7662e4f&los_type=track
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
XFH-Scheme: https://beta.spotify.com [421]
CacheCand: https://holidayswithspotify.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://holidayswithspotify.com [301]
XFH-Scheme: https://api-partner.spotify.com [204]
XFH-Scheme: https://admin.adanalytics.spotify.com [200]
CacheCand: https://adsmanager.spotify.com responds 301 to X-Forwarded-Host: evil.com
XFH-Scheme: https://adsmanager.spotify.com [301]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

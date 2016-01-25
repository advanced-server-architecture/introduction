# Intro

All credentials&tokens are authenticated/deliveried through `User Server`, token will describe applied scope/namespace (individual servers )

## User Server

#### GET /token?appid=APPID&secret=APPSECRET

>Get application token (to be used on the server side)

>return:
```json
{
  "error_code": 0,
  "access_token":"ACCESS_TOKEN",
  "expires_in":7200,
  "scope":["profile","friends"]
}
```

#### GET /authorize?appid=APPID&redirect_uri=REDIRECT_URI&state=STATE#wechat_redirect

> Web authorize

####

# okta-oauth2-proxy
Add Auth to Any App with OAuth2 Proxy


### Prerequisites
1. docker installed
2. docker compose installed

### Create .env file in the below format
```
OIDC_ISSUER_URL=<<replace with your issuer>>
CLIENT_ID=<<client id>>
CLIENT_SECRET=<<client secret>
COOKIE_SECRET=<<cookie secret 32 byte>>
```

### start the service
```
docker compose up
```

### Reference
[Oauth2 Proxy](https://github.com/oauth2-proxy/oauth2-proxy)
[Okta integration](https://developer.okta.com/blog/2022/07/14/add-auth-to-any-app-with-oauth2-proxy)
[JWT](https://jwt.io/)
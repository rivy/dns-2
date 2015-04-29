# DNS

## [DNSimple API](https://developer.dnsimple.com/domains)

### Examples

#### [List domains](https://developer.dnsimple.com/domains/#list)

```
set DNSimple_id=...
set DNSimple_token=...
curl --insecure -H "X-DNSimple-Token: %DNSimple_id%:%DNSimple_token%" -H "Accept: application/json" https://api.dnsimple.com/v1/domains
```

#### [Get a domain](https://developer.dnsimple.com/domains/#get)

```
set DNSimple_id=...
set DNSimple_token=...
curl --insecure -H "X-DNSimple-Token: %DNSimple_id%:%DNSimple_token%" -H "Accept: application/json" https://api.dnsimple.com/v1/domains/northernlogic.com

```

#### [List records for a domain](https://developer.dnsimple.com/domains/records/#list)

```
set DNSimple_id=...
set DNSimple_token=...
curl --insecure -H "X-DNSimple-Token: %DNSimple_id%:%DNSimple_token%" -H "Accept: application/json"  https://api.dnsimple.com/v1/domains/northernlogic.com/records

```

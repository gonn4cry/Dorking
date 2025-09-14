# Shodan Dorks for Bug Bounty

---

### Kibana

```
ssl.cert.subject.CN:"example.com" title:"kibana" port:"443"
```

### Kibana

```
ssl.cert.subject.CN:"example.com" X-App-Name: kibana
```

### Kibana

```
ssl.cert.subject.CN:"example.com" kbn-name: kibana
```

### Kibana
```
ssl.cert.subject.CN:"example.com" kibana content-length:217
```

### FTP Servers

```
ssl.cert.subject.CN:"example.com" "230 login successful" port:"21"
```

### FTP Servers

``` 
ssl.cert.subject.CN:"example.com" vsftpd 2.3.4 port:21
```

### FTP Servers

```
ssl.cert.subject.CN:"example.com" 230 'anonymous@' login ok
```

### FTP Servers

```
ssl.cert.subject.CN:"example.com" vsftpd 3.0.3
```

### VPN / WebVPN

```
ssl.cert.subject.CN:"example.com" "set-cookie: webvpn;"
```

### VPN / WebVPN 
```
ssl.cert.subject.CN:"example.com" "Set-Cookie: webvpn"
```

### VPN / WebVPN

```
ssl.cert.subject.CN:"example.com" "Set-Cookie:webvpnlogin=1"
```

### Siemens / ICS

```
ssl.cert.subject.CN:"example.com" Siemens S7 
```

### Database Management

```
ssl.cert.subject.CN:"example.com" "Set-Cookie: phpMyAdmin"
```

### Database Management

```
ssl.cert.subject.CN:"example.com" "Set-Cookie: mongo-express="
```

## Database Management

```
ssl.cert.subject.CN:"example.com" product:mongodb
```

### Gitlab
```
ssl.cert.subject.CN:"example.com" Set-Cookie: _gitlab_session
```

### Elasticsearch / Metrics

```
ssl.cert.subject.CN:"example.com" "X-elastic-product: Elasticsearch"
```

### Elasticsearch / Metrics

```
ssl.cert.subject.CN:"example.com" product:elastic port:9200
```

### Elasticsearch / Metrics

```
inurl:email= | inurl:phone= | inurl:password= | inurl:secret= inurl:& site:example[.]com
```

### Elasticsearch / Metrics

```
inurl:/content/usergenerated | inurl:/content/dam | inurl:/jcr:content | inurl:/libs/granite | inurl:/etc/clientlibs | inurl:/content/geometrixx | inurl:/bin/wcm | inurl:/crx/de site:example[.]com
```

### Disclosed XSS and Open Redirects

```
site:openbugbounty.org inurl:reports intext:"example.com"
```

### Google Groups

```
site:groups.google.com "example.com"
```

### Code Leaks

```
site:pastebin.com "example.com"
```

```
site:jsfiddle.net "example.com"
```

```
site:codebeautify.org "example.com"
```

```
site:codepen.io "example.com"
```

### Cloud Storage

```
site:s3.amazonaws.com "example.com"
```

```
site:blob.core.windows.net "example.com"
```

```
site:googleapis.com "example.com"
```

```
site:drive.google.com "example.com"
```

```
site:dev.azure.com "example[.]com"
```

```
site:onedrive.live.com "example[.]com"
```

```
site:digitaloceanspaces.com "example[.]com"
```

```
site:sharepoint.com "example[.]com"
```

```
site:s3-external-1.amazonaws.com "example[.]com"
```

```
site:s3.dualstack.us-east-1.amazonaws.com "example[.]com"
```

```
site:dropbox.com/s "example[.]com"
```

```
site:box.com/s "example[.]com"
```

```
site:docs.google.com inurl:"/d/" "example[.]com"
```

### JFrog Artifactory

```
site:jfrog.io "example[.]com"
```

### Firebase

```
site:firebaseio.com "example[.]com"
```

## Dorks that work better w/o domain

### Bug Bounty programs and Vulnerability Disclosure Programs <!--omit-->

```
"submit vulnerability report" | "powered by bugcrowd" | "powered by hackerone"
```

```
site:*/security.txt "bounty"
```

### Apache Server Status Exposed <!--omit-->

```
site:*/server-status apache
```

### WordPress <!--omit-->

```
inurl:/wp-admin/admin-ajax.php
```

### Drupal <!--omit-->

```
intext:"Powered by" & intext:Drupal & inurl:user
```

### Joomla <!--omit-->

```
site:*/joomla/login
```


---

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

### SQLi Prone Parameters

```
ssl.cert.subject.CN:"example.com"
```

### SSRF Prone Parameters

```
ssl.cert.subject.CN:"example.com"
```

### LFI Prone Parameters

```
inurl:include | inurl:dir | inurl:detail= | inurl:file= | inurl:folder= | inurl:inc= | inurl:locate= | inurl:doc= | inurl:conf= inurl:& site:example.com
```

### RCE Prone Parameters

```
inurl:cmd | inurl:exec= | inurl:query= | inurl:code= | inurl:do= | inurl:run= | inurl:read=  | inurl:ping= inurl:& site:example.com
```

### File upload endpoints

```
site:example.com ”choose file”
```

### API Docs

```
inurl:apidocs | inurl:api-docs | inurl:swagger | inurl:api-explorer site:"example[.]com"
```

### Login Pages

```
inurl:login | inurl:signin | intitle:login | intitle:signin | inurl:secure site:example[.]com
```

### Test Environments

```
inurl:test | inurl:env | inurl:dev | inurl:staging | inurl:sandbox | inurl:debug | inurl:temp | inurl:internal | inurl:demo site:example.com
```

### Sensitive Documents

```
site:example.com ext:txt | ext:pdf | ext:xml | ext:xls | ext:xlsx | ext:ppt | ext:pptx | ext:doc | ext:docx
intext:“confidential” | intext:“Not for Public Release” | intext:”internal use only” | intext:“do not distribute”
```

### Sensitive Parameters

```
inurl:email= | inurl:phone= | inurl:password= | inurl:secret= inurl:& site:example[.]com
```

### Adobe Experience Manager (AEM)

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

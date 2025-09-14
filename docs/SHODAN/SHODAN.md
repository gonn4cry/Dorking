# Shodan Dorks for Bug Bounty

---

### Kibana

```
ssl.cert.subject.CN:"example.com" title:"kibana" port:"443"
```

```
ssl.cert.subject.CN:"example.com" X-App-Name: kibana
```

```
ssl.cert.subject.CN:"example.com" kbn-name: kibana
```

```
ssl.cert.subject.CN:"example.com" kibana content-length:217
```

### FTP Servers

```
ssl.cert.subject.CN:"example.com" "230 login successful" port:"21"
```

``` 
ssl.cert.subject.CN:"example.com" vsftpd 2.3.4 port:21
```

```
ssl.cert.subject.CN:"example.com" 230 'anonymous@' login ok
```

```
ssl.cert.subject.CN:"example.com" vsftpd 3.0.3
```

### VPN / WebVPN

```
ssl.cert.subject.CN:"example.com" "set-cookie: webvpn;"
```

```
ssl.cert.subject.CN:"example.com" "Set-Cookie: webvpn"
```

```
ssl.cert.subject.CN:"example.com" "Set-Cookie:webvpnlogin=1"
```

```
ssl.cert.subject.CN:"example.com" Siemens S7 
```

### Database Management

```
ssl.cert.subject.CN:"example.com" "MongoDB Server Information" port:27017
```

```
ssl.cert.subject.CN:"example.com" "Set-Cookie: phpMyAdmin"
```

```
ssl.cert.subject.CN:"example.com" "Set-Cookie: mongo-express="
```

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

```
ssl.cert.subject.CN:"example.com" product:elastic port:9200
```

### Web / CMS Headers

```
ssl.cert.subject.CN:"example.com" X-Magento-Cache-Debug
```

```
ssl.cert.subject.CN:"example.com" WWW-Authenticate
```

```
ssl.cert.subject.CN:"example.com" x-drupal-cache
```

```
ssl.cert.subject.CN:"example.com" http.title:"django"
```

```
ssl.cert.subject.CN:"example.com" http.title:"react"
```

```
ssl.cert.subject.CN:"example.com" X-Generator: Drupal 7
```

```
ssl.cert.subject.CN:"example.com" http.component:"Drupal"
```

### Swagger UI

```
ssl.cert.subject.CN:"example.com" http.title:"Swagger UI"  
```

### Jenkins

```
ssl.cert.subject.CN:"example.com" html:Dashboard Jenkins http.component:jenkins
```

```
ssl.cert.subject.CN:"example.com" product:jenkins
```

### Apache/Tomcat

```
ssl.cert.subject.CN:"example.com" product:apache tomcat
```

```
ssl.cert.subject.CN:"example.com" "Tomcat" admin
```

### Citrix / Remote Access

```
ssl.cert.subject.CN:"example.com" "Citrix Gateway"
```

```
ssl.cert.subject.CN:"example.com" html:/dana-na/
```

```
ssl.cert.subject.CN:"example.com" authentication disabled RFB 003.008
```

### Telnet / RootAccess

```
ssl.cert.subject.CN:"example.com" root@ port:23 -login -password -name -Session
```

### Network

```
ssl.cert.subject.CN:"example.com" Server: NessusWWW
```

### Admin Panel

```
ssl.cert.subject.CN:"example.com" http.html:"admin panel"
```

### Directory Listing

```
ssl.cert.subject.CN:"example.com" http.title:"Index of"
```

### PHP

```
ssl.cert.subject.CN:"example.com" http.component:php
```

### ASPX
```
ssl.cert.subject.CN:"example.com" http.component:asp.net
```

### Forgotten Hosts

```
ssl.cert.subject.CN:"example.com" ssl.cert.expired: true 
```

### Authentication endpoints
```
ssl.cert.subject.CN:"example.com" http.title:Login
```

```
ssl.cert.subject.CN:"example.com" http.title:Log in
```

```
ssl.cert.subject.CN:"example.com" http.title:Signin
```

```
ssl.cert.subject.CN:"example.com" http.title:Register
```

```
ssl.cert.subject.CN:"example.com" http.title:Sign in
```

```
ssl.cert.subject.CN:"example.com" http.title:Sign up
```

### 302 Redirect

```
ssl.cert.subject.CN:"example.com" http.status:301,302,303
```

### Atlassian Confluence

```
ssl.cert.subject.CN:"example.com" http.html:"Atlassian Confluence" port:8090
```

### Connector UI

```
ssl.cert.subject.CN:"example.com" http.title:"Connector UI"
```

### Juicy Keywords

```
ssl.cert.subject.CN:"example.com" http.title:"manager"
```

```
ssl.cert.subject.CN:"example.com" http.title:"backend"
```

```
ssl.cert.subject.CN:"example.com" http.html:"admin"
```

```
ssl.cert.subject.CN:"example.com" http.title:"database"
```

```
ssl.cert.subject.CN:"example.com" http.title:"settings"
```

```
ssl.cert.subject.CN:"example.com" http.title:"setup"
```

```
ssl.cert.subject.CN:"example.com" http.title:"control"
```

```
ssl.cert.subject.CN:"example.com" http.title:"welcome"
```

```
ssl.cert.subject.CN:"example.com"  http.title:"monitor"
```

```
ssl.cert.subject.CN:"example.com"  http.title:"api"
```

```
ssl.cert.subject.CN:"example.com" http.title:"payment"
```

```
ssl.cert.subject.CN:"example.com" http.title:"console"
```

```
ssl.cert.subject.CN:"example.com" http.title:"terminal"
```

```
ssl.cert.subject.CN:"example.com" http.title:"configuration"
```

```
ssl.cert.subject.CN:"example.com" http.title:"config"
```

```
ssl.cert.subject.CN:"example.com" http.title:"devops"
```

```
ssl.cert.subject.CN:"example.com" http.title:"system"
```

```
ssl.cert.subject.CN:"example.com" http.title:"documentation"
```

```
ssl.cert.subject.CN:"example.com" http.html:"password"
```

```
ssl.cert.subject.CN:"example.com" http.title:"admin"
```

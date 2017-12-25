# This is a experimental project, and it works fine on 25-12-2017

# Cloudflare java bypass
This is an experimental project which can be used in order to skip the DDOS protection given by cloudflare.

This library is oriented to the web crawling, so I used the JSoup library and return a JSoup object when requesting an URL.

## How to use

Simply:

```java
CHttpRequester requester = new CHttpRequester();
requester.get("www.mysite-under-clodflare-or-not.com")
```
## Based in
- Java 9
- JSoup
## How it works
This library simply executes the javascript snippet used by cloudfare in order to avoid the DDOS attack.
It detects if a website is under this firewall, and if it is, it waits 5 seconds before resolve the callenge which will lead us to the actual website we are requesting.

## Contact

email: juan.roldan.brz@gmail.com

linkedn: https://www.linkedin.com/in/juan-bermudez-roldan-65725bb1/

##Feel free to experiment and contribute!


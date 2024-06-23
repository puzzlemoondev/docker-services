# alist_aria2

alist + aria2 + ariang

[aria2-ariang](https://github.com/hurlenko/aria2-ariang-docker) puts aria2 and ariang under reverse proxy so https connection can work in browser

## Environment Variables

- RPC_SECRET
- BASIC_AUTH_USERNAME
- BASIC_AUTH_PASSWORD

## Post-Deploy

- Set aria2 address in alist to http://aria2:8080/jsonrpc
- Set aria2 address in ariang to deployed domain

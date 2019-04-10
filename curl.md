---
layout: page
title: curl
docs: https://curl.haxx.se/docs/
---
GET request to `https://somewhere.com`
```bash
curl -X GET https://somewhere.com
```
POST request, with header
```bash
curl -X POST -H "Content-Type: application/json" https://somewhere.com
```
POST request, with header and data (containing json)
```bash
curl -X POST -H "Content-Type: application/json" -d '{"answer":"42"}' https://somewhere.com
```
Curl request with username `user` and password `password`
```
curl -u user:password https://somewhere.com
```
Download file `example.pdf` to `./example.pdf`
```
curl -O https://somewhere.com/example.pdf
```
Download file `example.pdf` to `./manual.pdf`
```
curl -o manual.pdf https://somewhere.com/example.pdf
```
Follow redirects
```
curl -L https://google.com
```
A short summary of curl:
- `curl https://github.com` defaults to a GET request
- using `-u` without specifying a password will cause curl to ask for one

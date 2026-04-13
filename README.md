# WhatAreBest.com

Static review/affiliate site hosted on GitHub Pages.

## Setup
1. Push this repo to GitHub
2. Enable GitHub Pages (Settings → Pages → Deploy from branch: `main`)
3. Update GoDaddy DNS:
   - CNAME: `www` → `<username>.github.io`
   - A records for apex:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
4. GitHub auto-provisions SSL certificate

## Amazon Associate Tag
`brazenprodu01-20`

## Structure
```
index.html              — Homepage
about.html              — About page
CNAME                   — Custom domain config
automotive/             — Automotive reviews
  best-jeep-seat-covers.html
home/                   — Home & HVAC reviews
  best-hvac-filters.html
```

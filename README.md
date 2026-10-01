# Qinwan Agency — Website

Helping ambitious companies expand and grow in the UAE.
Domain: **qinwan.agency** · Qinwan Marketing Management L.L.C S.O.C — Dubai, UAE

## Structure

```
index.html              Production site (self-contained: fonts, photo, scripts inlined)
docs/QINWAN_CONTEXT.md  Brand & project source of truth
source/                 Editable design source + assets
```

## Deploy on Vercel

1. Push this repo to GitHub.
2. vercel.com → Add New → Project → import the repo.
   Framework preset: **Other**. No build command. Output directory: `.` (root).
3. Settings → Domains → add `qinwan.agency` (and `www.qinwan.agency`), then add the DNS records Vercel shows at your domain registrar.

## Contact form

Currently opens the visitor's email app with a pre-filled request to kacibouabida@qinwan-marketing.com.
To do: connect a form service (e.g. Web3Forms) so requests are sent directly.

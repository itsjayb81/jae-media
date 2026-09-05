# ⚠️ THIS IS NOT THE LIVE AJ SHINE SITE

**ajshine.com.au is served from a different repo: `github.com/itsjayb81/ajshine`**
(local: `C:\Users\itsja\Desktop\ajshine\`, which holds the CNAME).

This folder is a **duplicate** reachable at
`itsjayb81.github.io/jae-media/sites/aj-shine/`. Pushing here changes that URL
and **nothing else**. The custom domain will not move.

On 5 Sep 2026 Bob deployed here, watched ajshine.com.au for ten minutes, and
blamed a CDN cache. The cache expired and the page still had not changed,
because this was never the source.

**To deploy the site:**

    python trade-websites/build_site.py sites/aj-shine.json
    cp trade-websites/dist/aj-shine/index.html  C:\Users\itsja\Desktop\ajshine\index.html
    cd C:\Users\itsja\Desktop\ajshine && git add -A && git commit && git push

Kept rather than deleted in case the github.io URL is linked from an old post
or QR code. If nothing points at it, delete the folder.

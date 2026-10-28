# Theron and Prince Solutions website

## Where this lives

- **Code:** GitHub, account `Brynne98`, repo `Brynne98/theronprince-site` (public).
- **Remote:** `origin` = `git@github.com:Brynne98/theronprince-site.git`, SSH.
  `ssh -T git@github.com` must answer "Hi Brynne98!" before any push.
- **Branch:** `main`.
- **Host:** Cloudflare Pages project `theronprince-site` (theronprince-site.pages.dev),
  rebuilt from `main` on every push. Build command `mkdir -p out && cp index.html out/`,
  output `out`, so only index.html is served. Custom domains theronprince.co.za and
  www.theronprince.co.za. GitHub Pages is off since 2026-10-28 (SOLAR-213); the `CNAME`
  file in the repo is left over from it.
- **DNS:** Cloudflare zone theronprince.co.za (nameservers clayton/jacqueline.ns.cloudflare.com
  since 2026-10-28). The domain is still registered and paid at xneelo (create.xneelo.com,
  account C1014070126). Google Workspace mail records live in the zone: MX, SPF, DKIM, DMARC,
  and the apex google-site-verification TXT (Search Console and the Play account, SOLAR-211,
  depend on it). Leave them alone.
- **Issues:** Plane, workspace `brynne98`, project **Prince Solar** (`SOLAR-*`).

## Releasing

```bash
git push origin main
```

Push only on Brynne's explicit say-so.

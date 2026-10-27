# Theron and Prince Solutions website

## Where this lives

- **Code:** GitHub, account `Brynne98`, repo `Brynne98/theronprince-site` (private).
- **Remote:** `origin` = `git@github.com:Brynne98/theronprince-site.git`, SSH.
  `ssh -T git@github.com` must answer "Hi Brynne98!" before any push.
- **Branch:** `main`.
- **Host:** Cloudflare Pages project `theronprince-site`, serving the repo root at
  theronprince.co.za. Rebuilt from `main` on every push. No build step.
- **DNS:** Cloudflare (moved from xneelo for SOLAR-207). Registrar is xneelo, company
  account. Google Workspace mail records (MX, SPF, DKIM, DMARC) live in this zone.
- **Issues:** Plane, workspace `brynne98`, project **Prince Solar** (`SOLAR-*`).

## Releasing

```bash
git push origin main
```

Push only on Brynne's explicit say-so.

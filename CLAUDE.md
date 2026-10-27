# Theron and Prince Solutions website

## Where this lives

- **Code:** GitHub, account `Brynne98`, repo `Brynne98/theronprince-site` (public; GitHub Pages
  on the free plan needs a public repo).
- **Remote:** `origin` = `git@github.com:Brynne98/theronprince-site.git`, SSH.
  `ssh -T git@github.com` must answer "Hi Brynne98!" before any push.
- **Branch:** `main`.
- **Host:** GitHub Pages from `main`, repo root, custom domain theronprince.co.za, https
  forced (Let's Encrypt via GitHub). www redirects to the apex. Rebuilt on every push.
- **DNS:** xneelo Manage DNS (create.xneelo.com, company account C1014070126). Apex has
  GitHub's four A records (185.199.108-111.153); www is a CNAME to brynne98.github.io.
  Google Workspace mail records (MX, SPF, DKIM, DMARC) live there too; leave them alone.
- **Unused, set up for a later move:** Cloudflare Pages project `theronprince-site`
  (theronprince-site.pages.dev) and a pending Cloudflare zone for theronprince.co.za
  (nameservers clayton/jacqueline.ns.cloudflare.com). The xneelo nameserver change was
  locked on 2026-10-27. Before any move, add the `relay` CNAME to the Cloudflare zone and
  apex/www records for Pages.
- **Issues:** Plane, workspace `brynne98`, project **Prince Solar** (`SOLAR-*`).

## Releasing

```bash
git push origin main
```

Push only on Brynne's explicit say-so.

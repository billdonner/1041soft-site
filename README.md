# 1041soft.com

Company site and App Store support/privacy pages for 1041Soft apps.

**Public on purpose.** GitHub Pages builds free for public repos; on a private
repo every push would bill against the account's Actions minutes. Do not enable
Pages on the individual app repos (`mallinbook`, `sentipods`, `pfolio-app` are
private) — add pages here as subpaths instead.

Plain static HTML, no build step. Edit and push; Pages serves it.

```
/                    landing
/screenker/          support      /screenker/privacy
/mallinbook/         support      /mallinbook/privacy
/sentipods/          support      /sentipods/privacy
/pfolio/             support      /pfolio/privacy
```

Every privacy page carries a TODO block that must be answered from the shipping
build before that app is submitted. They are deliberately not filled in with
guesses — a privacy policy is a representation to users and to Apple.

## Unified app portfolio (September 2026)

1041Soft is the home for all apps, including AmenBeats, MURDL 16, 123 Words,
100 Burfords, PickledBalls, and workinOn previously listed at BillDonner.com.
`data/portfolio.json` shares descriptions and company URLs with the personal
site's `build_apps.py --catalog ../1041soft-site/data/portfolio.json` workflow.
Update the company HTML alongside the catalog when changing copy. Existing
App Store IDs and TestFlight links are preserved; transfer alone does not imply
that an app has been released. Support pages and policy text were carried over
from their existing sources, with navigation and support contacts updated.

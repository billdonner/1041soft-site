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

# AdsCraft — Bug reports

Issue tracker for **AdsCraft**, a playable-ads platform for Cocos Creator: build the playable locally,
configure it on the cloud, and export a size-checked package for each ad network.

This repository holds **no source code** — it exists only to collect bug reports, documentation gaps,
and feature requests from AdsCraft users.

**[Open a new issue ▸](https://github.com/blackbeans-1301/adscraft-bugs-report/issues/new)**

## Before you file

- Search the [existing issues](https://github.com/blackbeans-1301/adscraft-bugs-report/issues) to avoid
  duplicates.
- Read the docs at [docs.adscraft.app](https://docs.adscraft.app) — the answer may already be there.

## What to include

A clear report lets us reproduce the problem without guessing. Please add:

- **Steps to reproduce** — the exact steps, and where you hit them (the Cocos Creator panel, or the
  dashboard at [playground.adscraft.app](https://playground.adscraft.app)).
- **Expected vs. actual** — what you thought would happen, and what happened instead.
- **Environment** — Cocos Creator version, AdsCraft extension/SDK version, the ad network involved,
  and your browser/OS.
- **Evidence** — a screenshot, the error text, or the download `manifest.csv` when relevant.

> **Never paste secrets.** Redact API tokens, `AUTH_SECRET`, R2 access keys, store credentials, and any
> private preview link before posting.

## Scope

| In scope | Out of scope |
|---|---|
| Bugs in the extension, SDK, dashboard or preview | Security vulnerabilities → report privately, see below |
| Documentation errors and unclear instructions | Issues inside the ad networks' own platforms |
| Feature requests for AdsCraft | Debugging your specific game code |

## Security

Please **do not** open a public issue for a security vulnerability. Contact the maintainers privately
first, so it can be fixed before any public disclosure.

## Links

- Documentation — <https://docs.adscraft.app>
- Landing — <https://adscraft.app>
- Dashboard — <https://playground.adscraft.app>

---

AdsCraft supports Cocos Creator **3.8.8+** and ships one payload sized against **21 ad networks**;
Unity Ads is verified end-to-end, the rest are packaged and awaiting a real upload test.

# TapVault

**NFC Library for iPhone & iPad**

Public product website, support and development-stage privacy information. Based on [cloudlatch-site](https://github.com/Chrominskyy/cloudlatch-site), adapted to TapVault. Application source is maintained separately.

## Website

https://chrominskyy.github.io/tapvault-site/

- Product overview: `index.html`
- Setup and reports: `support.html`
- Data handling: `privacy.html`
- Shared light/dark stylesheet: `css/main.css`
- NFC illustration: `assets/nfc-orbit.png`, reused from TapVault’s existing app artwork.

The app is under development. No App Store release, download URL or final privacy disclosure is claimed. The website uses no JavaScript, remote fonts or analytics.

## Reports

[Choose a report](https://github.com/Chrominskyy/tapvault-site/issues/new/choose): bug, incident, feature request or support question. English and Polish are welcome. Incidents include impact, timeline with timezone, environment and recovery. Read [CONTRIBUTING.md](CONTRIBUTING.md), [SECURITY.md](SECURITY.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before posting. Never attach real NFC payloads, tag identifiers, personal data or private diagnostics.

## Development

No dependencies or build step.

```sh
python3 scripts/check_site.py
python3 -m http.server 8765 --bind 127.0.0.1
```

GitHub Pages publishes `main` from `/`, with HTTPS, matching the reference repository. `main` requires one approving review, code owner review, stale review dismissal and conversation resolution. Administrator enforcement is disabled, matching the reference.

Before distribution, verify physical NFC operations, cross-device synchronization, final privacy disclosures and an approved download URL.

# Security Policy

## Reporting a vulnerability

Please **do not** report security vulnerabilities through public GitHub issues.

Instead, report them privately via [GitHub Security Advisories](https://github.com/Abdullah-Chaudary/doppler-geolocator/security/advisories/new) (Report a vulnerability).

Include as much detail as you can:

- Description of the issue and potential impact
- Steps to reproduce
- Affected version / commit

You should receive an acknowledgement within a few days. Please allow reasonable time for a fix before any public disclosure.

## Scope

This project is a client-side web app: audio and ADSB data never leave your browser. In scope:

- XSS or script injection via crafted audio filenames, CSV contents, or GeoJSON
- Any unexpected exfiltration of user data
- Supply-chain issues in CDN dependencies (Leaflet)

Out of scope:

- The inherent dual-use nature of the geolocation technique itself (see README → Ethical Use)
- Issues requiring a malicious local filesystem or compromised OS

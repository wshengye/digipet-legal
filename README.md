# digipet-legal

Public legal, privacy, and support pages for the
[Digipet](https://github.com/wshengye/digipet-app) iOS app. Deployed via
Cloudflare Pages at `legal.digipetsg.app` and referenced from App Store Connect
and Supabase auth settings.

- [Privacy Policy](https://legal.digipetsg.app/privacy)
- [Terms of Service](https://legal.digipetsg.app/terms)
- [Support](https://legal.digipetsg.app/support)

The in-app copies (`app/privacy.tsx` and `app/terms.tsx` in the main repo) are
the source of truth for the privacy and terms text; this repo is updated when
those change. `support.html`, `confirmed.html` (email-confirmation landing),
and `reset-password.html` are web-only pages with no in-app equivalent.

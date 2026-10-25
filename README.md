# chorito-legal

Public legal pages for [Chorito](https://github.com/aaronmusa/chorito-ios), a household chores app for iPhone.

Kept in its own repo so the copy can be corrected without shipping an app release.

| Page | URL |
|---|---|
| Landing | `/` |
| Privacy Policy | `/privacy/` |
| Support | `/support/` |
| Terms of Use | Apple's Standard EULA (linked out, not hosted here) |

## Deploying

GitHub Pages, deploying from `main` at the repo root. Push to `main` and Pages republishes.

## Rules

- The privacy policy must keep matching the app's `PrivacyInfo.xcprivacy` and the App Store Connect privacy answers. If one changes, change all three.
- Anything new the app stores, or anyone new who can see it (a new SDK, a new service), is a privacy policy edit as well as a code change.

# paperlight-privacy

The privacy policy for [Paperlight](https://apps.apple.com/app/id6800686635), served by
GitHub Pages at **https://ardathepolatserve.github.io/paperlight-privacy/**

That URL is referenced from two places and must not move without updating both:

- `PaywallView.defaultPrivacyURL` in the app — App Review opens it from the buy screen, and
  `PolicyLinkTests` fails the build if it reverts to a placeholder.
- The App Store Connect listing's Privacy Policy URL.

## Editing

Plain HTML, no build step. `index.html` is the page, `style.css` carries Paperlight's own
colour tokens so it matches the app in light and dark. `.nojekyll` keeps GitHub from running
Jekyll over it.

**The policy must stay true.** It claims the app has no server, collects nothing and runs
text recognition on-device. If that ever stops being true, this page changes *before* that
version ships — `docs/submission/PRIVACY_LABEL.md` in the app repo is the matching record of
what the code actually does.

# ClearSubs — legal documents

Published privacy policy for the ClearSubs iOS app by Andrii Svitelskyi:

- **Privacy Policy** — https://andriiseeker.github.io/clearsubs-legal/privacy-policy.html

This is the URL referenced from App Store Connect and opened from inside the app, so it must keep
working: do not rename the files, do not rename this repository, and do not disable GitHub Pages.

## Updating

1. Edit the HTML directly.
2. Update the `Effective date` and `Last updated` lines in the file you changed.
3. Commit and push to `main`. GitHub Pages redeploys within a minute or two.

Announce material changes inside the app before they take effect.

## When this document must be revisited

- a new SDK, analytics or crash reporting tool is added;
- accounts, sync or user-generated content appear in the app;
- data starts leaving the device, or starts going to a new third party (including AI providers);
- the app changes its audience (for example, becomes directed to children);
- one of the network hosts in section 6 changes.

The answers in App Store Connect → App Privacy must always match what the Privacy Policy says.

## Layout

```
index.html              landing page
privacy-policy.html     Privacy Policy
styles.css              shared styles, no external dependencies
.nojekyll               serve files as-is, without Jekyll processing
```

---

Populated with the app's actual data practices. **Not legal advice**: have a lawyer review the
document before release. Contact: [andriy.svitelskyi@gmail.com](mailto:andriy.svitelskyi@gmail.com)

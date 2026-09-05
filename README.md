# tritonal75.github.io

The public homepage and privacy policy for **Daffodil Gmail Automation**, a
personal command-line tool for one person's own Gmail account.

These pages exist because Google's OAuth consent screen requires a homepage and
a privacy policy URL before an app can be published out of Testing status, where
refresh tokens are expired after 7 days.

- <https://tritonal75.github.io/>
- <https://tritonal75.github.io/privacy.html>

## Why this repo is named this way

GitHub publishes a repository named `<username>.github.io` at the domain root
rather than under a subpath. The root is required here because Google Search
Console verifies domain ownership by fetching a file from it — the
`google<hash>.html` in this repo — and that verification is what allows
`tritonal75.github.io` to be added to the OAuth consent screen's authorized
domains.

This repository is public only because free GitHub Pages requires it. It holds
nothing but these pages. The tool itself is private.

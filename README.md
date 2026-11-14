# Super Jackfruit Labs public profile

[![Profile: public](https://img.shields.io/badge/profile-public-blue)](profile/README.md)

The organization landing page is maintained in
[`profile/README.md`](profile/README.md) and appears on the
[Super Jackfruit Labs organization page](https://github.com/SuperJackfruitLabs).

Edit that file to update the public introduction and product navigation. Keep
product details in their own READMEs, link release claims to actual releases,
and keep private operational material in its owning private repository.

For changes, preview the Markdown, verify repository and release links, and run
`git diff --check`. This repository has no application build, CI workflow, or
top-level license file.

## Renovate presets

`renovate/` holds the suite's shared [Renovate](https://docs.renovatebot.com) presets. They are
public so that every repository, on GitHub or on the suite's forge, can extend them without a
token.

- `renovate/vibekit.json` watches only the vibekit packages (`@superjackfruitlabs/vibekit-ui`,
  `@superjackfruitlabs/vibekit-frame`, `@superjackfruitlabs/vibekit-docs`), in one grouped pull
  request, and never merges it.
- `renovate/vibekit-automerge.json` is the same, merged by Renovate once every status check on
  the pull request has passed.

A repository extends one in its `renovate.json`:

```json
{ "extends": ["github>SuperJackfruitLabs/.github//renovate/vibekit-automerge"] }
```

Check a change with `npx --package renovate@44.198.3 renovate-config-validator --strict --no-global renovate/*.json`.

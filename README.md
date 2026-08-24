# featherdb-releases

Downloadable release assets for [FeatherDB](https://featherdb.dev/) — the
`.dmg` and `.delta` files Sparkle and the Homebrew cask point at.

No source code here on purpose: this repo is public so the files can be
downloaded anonymously (by Sparkle, by `brew install`, by anyone), while the
app's source stays in the private
[featherdb](https://github.com/featherdb-app/featherdb) repo.

Cut with `frontend/scripts/ship.sh DIRECT_DISTRIBUTION=1` in that repo — see
`docs/RELEASING.md` there for the full runbook. Every asset here is signed,
notarized, and stapled before it's uploaded; nothing is built in this repo.

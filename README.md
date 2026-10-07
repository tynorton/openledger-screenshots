# openledger-screenshots

Public screenshots embedded in pull request descriptions of the private OpenLedger repo. GitHub's mobile app cannot show images
from a private repo inline, so PR screenshots live here instead.

Everything here shows sandbox or seeded test data only. Never add a screenshot with real accounts, balances, names or emails.

Every shot comes in two variants, `<name>.png` (light) and `<name>-dark.png` (dark), embedded together with `<picture>` so readers see the one matching their theme (OpenLedger's `scripts/screenshots.sh` takes both). README images live under `readme/`.

Layout: `pr/<PR number>/<name>.png`. Embed with a commit-pinned raw URL:

```
https://raw.githubusercontent.com/tynorton/openledger-screenshots/<commit sha>/pr/<N>/<name>.png
```

Screenshots for pull requests of tynorton/claude-retirementcalc go under `retirementcalc/pr/<N>/<name>.png`, from its fictional sample household with a mocked OpenLedger.

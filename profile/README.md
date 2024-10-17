**This is where the magic happens :o**

Repository Names:

- `Project-Title`

Branches:

- `main` – most stable, should always be able to check out and provide a running game
- `release` – the actual release versions of the code; can be automated so that a push to this branch automatically builds & releases to Itch.io, etc.
- (`develop` – a branch for integrating & merging new features from their feature branches & testing them, fixing bugs, etc.) – only with multiple features in parallel
- `feature-xxx` – an arbitrary number of feature branches for developing singles features in relative isolation

Work with [GitHub Projects](https://docs.github.com/de/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects) & Issues.

Commits: Always mention issue, e.g. "added: Inventory sorting (#5)"

- `added: new feature added`
- `removed: feature that was removed`
- `improved: description of what was improved`
- `changed: feature that was changed`
- `fixed: brief description of problem`
- `cleaned: description of misc clean-up changes`
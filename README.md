# How to generate changelog using [standard-version](https://github.com/conventional-changelog/standard-version)

1. For the first release you need to run it:
```bash
npx standard-version --first-release
git push --follow-tags origin main
```
2. Then, it can be run with github actions (current example contains manual workflow trigger).
3. You need to follow [Conventional Commits specification](https://www.conventionalcommits.org/en/v1.0.0/) to generate changelog properly.

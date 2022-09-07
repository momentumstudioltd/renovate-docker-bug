# renovate-docker-bug
https://github.com/renovatebot/renovate/discussions/17363

## Expected Behaviour

Renovate should be tracking my private Docker images used in `.github/workflows/ci.yml` and create PRs for them where relevant.

## Actual Behaviour

Renovate shows an error on the Dependency Dashboard that states it cannot find our private docker images. They are hosted on GitHub Packages privately but we're using the official Renovate app so Renovate should automatically be able to access them.

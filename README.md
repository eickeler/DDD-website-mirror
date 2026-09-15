# GNU DDD Website Mirror

An automated, unofficial mirror of the
[GNU Data Display Debugger (DDD) website](https://www.gnu.org/software/ddd/).

- **Live mirror:** <https://eickeler.github.io/DDD-website-mirror/>
- **Upstream website:** <https://www.gnu.org/software/ddd/>
- **Update schedule:** weekly, using GitHub Actions
- **Source repository mirror:** <https://github.com/eickeler/DDD>

## Purpose

This repository provides a GitHub-hosted mirror of the public
[GNU DDD website](https://www.gnu.org/software/ddd/).

Its primary purpose is to reduce traffic to `www.gnu.org` by providing a 
publicly accessible copy through GitHub Pages. The mirror is updated
weekly, rather than on every visitor request.

This is an independent, unofficial mirror and is not an official GNU or Free
Software Foundation service. For authoritative information, releases, and
project announcements, please use the upstream website.

## Copyright and licensing

Copyright notices and licensing terms remain those supplied by the upstream
website and its individual files. In particular, this repository does not
change or grant additional rights for mirrored content.

## Updates

The site is refreshed once per week from:

<https://www.gnu.org/software/ddd/>

The update job uses rate limiting and retries to avoid unnecessary load on the
upstream server. If an update fails, the existing mirror remains published.

## Related repositories

- [DDD Git mirror](https://github.com/eickeler/DDD) — mirror of the DDD source repository
- [DDD-workflows](https://github.com/eickeler/DDD-workflows) — automation for the mirrors

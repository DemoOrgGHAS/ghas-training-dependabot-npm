# Safety notice
This repository is a static training fixture for GitHub security scanning.
- No malware, payloads, network listeners, authentication bypass, or working credentials.
- Do not deploy or execute the sample application code.
- All secrets are synthetic and intentionally invalid.
- Use only in a dedicated public training repository with no production data.

# Lab 3: Dependabot alerts and update PRs
Goal: demonstrate dependency graph, Dependabot alerts, and version-update pull requests.

This repository contains no JavaScript source, scripts, server, or deployment. `package.json` is metadata only. GitHub determines alerts from the current Advisory Database, so exact alerts may change. Do not run `npm install` or execute these packages.

Enable **Settings > Security > Dependabot alerts** and **Dependabot security updates**. The included configuration also requests weekly version-update PRs.

# Security policy

## Supported versions

Only the latest release of each card gets fixes. Please update before reporting.

## Reporting a vulnerability

Please **do not open a public issue** for a security problem.

Report it privately instead: open the repository of the affected card, go to the **Security** tab and click **Report a vulnerability**. Only the maintainer can see the report.

Useful details:

- the card and its version,
- what an attacker could do (for example run a script through a card option or an entity value),
- steps or a config to reproduce it.

You should get an answer within a week. Once a fix is released, the advisory is published and you are credited, unless you prefer not to be.

## Scope

These cards run in the Home Assistant frontend, in the browser of the person viewing the dashboard. Relevant reports include script injection through card options, templates or entity states, and loading of remote content. Problems in Home Assistant itself belong to the [Home Assistant project](https://www.home-assistant.io/security/).

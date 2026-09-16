# HexoMC Bot — Legal pages

Static, dependency-free pages intended for the public repository `HexoMC/hexomc-bot-legal`.

## Publication status

Source files for the public HexoMC bot legal website. The URLs below become available after GitHub Pages is enabled and its deployment succeeds.

## Publish

1. In Settings → Pages, choose Deploy from a branch → master → / (root), and Save.
2. Wait for deployment and verify both URLs in a signed-out browser.
3. In the Discord Developer Portal, enter:
   - Terms of Service: https://hexomc.github.io/hexomc-bot-legal/terms.html
   - Privacy Policy: https://hexomc.github.io/hexomc-bot-legal/privacy.html

## Operator review before publication

The data descriptions were prepared from the current bot implementation, including database migrations and message logging. Operational practices cannot be confirmed from source code alone. Before publication:

- Ensure the contact path works: server staff must route requests to the bot operator and GitHub contact issues must be monitored. A dedicated monitored email or support URL is preferable; replace the contact paragraph in both pages if available.
- Ensure deletion requests are actually handled across database records, Discord log messages and any backups, including when the service stops. The examined schema does not impose automatic expiry on all records; the pages deliberately promise no invented fixed retention period.
- Confirm actual hosting providers, access controls, backup practices, jurisdiction-specific disclosures and processing match the policy; add details required for your operation.
- Make these links accessible from the bot (for example its help response) and notify users about logging.
- Update the date if publication happens later.

Providing these pages does not itself verify the bot. Discord separately reviews applications and requested privileged intents.

## References

- https://support-dev.discord.com/hc/en-us/articles/8562894815383-Discord-Developer-Terms-of-Service
- https://support-dev.discord.com/hc/en-us/articles/8563934450327-Discord-Developer-Policy

No bot source, credentials, server IDs or private deployment configuration are included.

# Retrovee draft workflow

This edition builds on [zubair-trabzada/geo-seo-claude](https://github.com/zubair-trabzada/geo-seo-claude). Original copyright and licensing are in [LICENSE](LICENSE).

Upstream main branch ZIP SHA-256: `5eb9000f1218e9f372e07216f72c8446a6fb116e8370689ac7578d8eb6deb1ab`.

Use the [`retail-ai-visibility` skill](codex-skills/retail-ai-visibility/SKILL.md) for the Codex draft workflow. Copy the entire skill directory into your Codex skills directory. This skill has no runtime dependencies. The upstream tools retain their separate setup instructions in the original README.

Keep credentials, customer data and performance exports out of Git. Review proposed external changes and get approval before making them live.

## GitHub Actions

The original workflows are retained in `.github/upstream-workflows/` for review. Enable selected workflows only after checking their triggers, tokens and publish targets.

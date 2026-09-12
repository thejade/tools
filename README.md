# tools

Random tools that can be useful in some situations.

## CloudFlare

Some tools for CloudFlare's services.

## ForwardEmail

These are some tools I found useful for [ForwardEmail](https://forwardemail.com)'s
services. They have great API documentation [here](https://forwardemail.net/en/email-api).

## Claude Code

Configuration for [Claude Code](https://claude.com/claude-code).

[claude-telemetry.zsh](claude-code/claude-telemetry.zsh) — environment variables that disable
Claude Code's non-essential network traffic (usage analytics, error reporting, feature flags,
auto-updates, and the transcript-uploading `/bug` and `/feedback` commands). Source it from your
shell profile.

[status-line-prompt.md](claude-code/status-line-prompt.md) — prompt for generating the status line
script.

## Best Practices

Write-ups on engineering practice rather than code.

[Small-PRs.md](best-practices/Small-PRs.md) — the case for small pull requests: why review quality and
merge latency degrade with size, and the patterns for splitting work that *feels* atomic
(refactor-then-behave, vertical slices, expand/migrate/contract, stacked PRs, and dark launches).
# Weekly Roundup Builder

<p>
  <img alt="Status: Working tool" src="https://img.shields.io/badge/status-working%20tool-2563eb">
  <a href="LICENSE"><img alt="Licence: MIT" src="https://img.shields.io/badge/licence-MIT-lightgrey"></a>
</p>

Pull whatever data and findings you actually have this week into one honest report, without inventing a trend where no earlier report exists to compare against.

## Why

A weekly report is easy to get subtly wrong in two ways: claiming movement from a single snapshot with nothing to compare it to, and treating a section with no data as if it were a confirmed zero. This composes what genuinely exists, marks what is missing as missing, and only claims a trend once a real baseline exists.

[![Checks that prevent a weekly report confusing missing data with zero or a snapshot with a trend.](assets/diagrams/15-weekly-roundup-builder.svg)](SKILL.md)

## Use It

Copy [SKILL.md](SKILL.md) and paste it into your AI tool (ChatGPT, Claude, Gemini, or similar), then paste in whatever you actually have this period. It produces a report that:

- **Composes existing findings** rather than re-deriving analysis already done elsewhere
- **Never claims a trend** without a genuine earlier report to compare against
- **Separates missing from zero**, in both directions
- **Names specific priorities** drawn from this period's actual data, not generic advice

<details>
<summary><strong>See exactly what it produces</strong></summary>

1. Each section composed from what genuinely exists, with missing sections marked missing, not zero
2. A trend claim only where a genuine earlier report actually supports one
3. Specific priorities drawn from this period's data, not generic advice
4. Any request to estimate a missing figure, declined rather than quietly filled in

</details>

See [the worked example](example/): a fictional freelance designer's first-ever weekly roundup. For a harder second case, the same designer's following week, read [the second worked example](example-two/).

Use [the blank template](templates/roundup-template.md) for your own roundup, and [the review checklist](checks/checklist.md) before acting on anything it suggests.

No installation, project, or coding required to try it once.

## Before You Use It

This composes a report; it does not act on anything in it. Approving and acting on any suggested priority stays your own decision.

## Feedback

Used it for a real weekly roundup? [Start a discussion](https://github.com/shaunmarsden/weekly-roundup-builder/discussions) if something did not fit.

## Part of a Family

This is one of a family of free tools generalising [practical-ai-sales-workflows](https://github.com/shaunmarsden/practical-ai-sales-workflows) patterns beyond sales. See [sibling-projects](https://github.com/shaunmarsden/sibling-projects) for the rest. Not sure which one actually fits? Try [the interactive picker](https://shaunmarsden.github.io/sibling-projects/) for clickable cards, or [the router](https://github.com/shaunmarsden/sibling-projects/blob/main/ROUTER.md) if you would rather paste a description into an AI chat.

# Third-Party Methodology Notes

The KiKo social media skill is an original adaptation for Nacho Ecommerce and future KiKo client profiles.

It draws methodological inspiration from:

## Charlie Hills Social Media Skills

- Upstream: `charlie947/social-media-skills`
- License: MIT
- Concepts reviewed: shared voice context, content matrices, carousel approval gates, content scoring, and format-specific workflows.

## BlackTwist Social Media Skills

- Upstream: `blacktwist/social-media-skills`
- License: MIT
- Concepts reviewed: persistent social context, content strategy, calendar structure, platform-specific writing, repurposing, and performance analysis.

## Adaptation boundaries

KiKo does not depend on BlackTwist, Apify, Gemini, Claude-specific question tools, or automated publishing services.

The adapted workflow:

- Uses a Nacho-specific profile separated from reusable social strategy logic.
- Prioritizes Instagram, Uruguay, and Latin America.
- Connects content to free resources, owned contacts, diagnostics, and paid ecommerce services.
- Requires explicit approval before final design, publishing, scheduling, profile changes, or outreach.
- Uses current platform verification instead of freezing changing algorithm guidance into the skill.

Do not remove upstream license files from any copied third-party source. When importing substantial upstream text or code later, preserve its original copyright and MIT license notice.

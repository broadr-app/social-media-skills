# Social Media Skills by Broadr

AI agent skills for social media content creation, scheduling, and analytics. Built for Claude Code, Codex, Cursor, and any agent that supports the [Agent Skills spec](https://agentskills.io).

**What makes these different:** These skills don't just generate text — they connect to [Broadr's MCP server](https://broadr.app) to actually schedule posts, pull analytics, and manage your channels. No Broadr account? They work standalone too.

## Available Skills

| Skill | Description |
|-------|-------------|
| [content-repurposer](skills/content-repurposer/) | Turn one piece of long-form content into 10+ platform-native social media posts |

## Installation

```bash
# Install all skills
npx skills add broadr-app/social-media-skills

# Install a specific skill
npx skills add broadr-app/social-media-skills --skill content-repurposer
```

## Supported Platforms

LinkedIn, Instagram, TikTok, Facebook, Threads, Bluesky, Mastodon, YouTube

## How It Works

Each skill operates in two modes:

- **Broadr Mode** — If you have the [Broadr MCP server](https://broadr.app) connected, skills can read your channels, generate platform-adapted posts, preview them, and schedule directly.
- **Standalone Mode** — Without Broadr, skills generate platform-native content as text output. Connect Broadr later to unlock scheduling.

## Built by [Broadr](https://broadr.app)

Broadr is Linear for social media planning — fast, keyboard-driven workflows with AI integration for creators and teams.

## License

Apache-2.0

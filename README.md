# AI Social Media Agent

One-trigger automation that publishes AI-generated content simultaneously to 4 platforms.

## Result
**Content team eliminated manual publishing across 4 platforms.** One message → 4 platforms in seconds.

## How it works

1. Trigger message sent via Telegram with content brief
2. n8n workflow activates
3. Tavily web search fetches relevant current information
4. OpenAI GPT-4o generates platform-optimized text for each channel
5. OpenAI DALL-E generates accompanying image
6. Structured Output Parser formats content per platform requirements
7. Simultaneous publish to Instagram, Facebook, Threads & LinkedIn via Meta APIs

## Tech Stack

| Tool | Purpose |
|---|---|
| n8n | Workflow orchestration |
| OpenAI GPT-4o | Content generation |
| OpenAI DALL-E | Image generation |
| Tavily | Real-time web search |
| Meta Graph API | Instagram, Facebook, Threads |
| LinkedIn API | LinkedIn publishing |
| Telegram Bot API | Trigger interface |

## Key Features

- **Multi-platform** — 4 platforms from single trigger
- **AI-optimized content** — different tone/format per platform
- **Real-time research** — Tavily fetches current info before writing
- **Image generation** — automatic visuals for each post
- **Structured outputs** — consistent formatting via Output Parser

## Business Impact

- Eliminated 2-3 hours/day of manual publishing
- Consistent posting schedule across all platforms
- AI-researched content stays current and relevant

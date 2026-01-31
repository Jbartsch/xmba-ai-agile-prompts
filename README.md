# AI-Native Agile: Prompt Toolkit

Prompts for the xMba "Agile Work & Vibe Coding" workshop.

![AI-Native Agile Workflow](ai-agile-workflow.png)

## Prerequisites

Before the workshop, make sure you have accounts for these tools (all free):

| Tool | What it does | Sign up |
|------|-------------|---------|
| **Claude** | AI assistant (morning: backlog creation) | [claude.ai](https://claude.ai) |
| **Linear** | Project management (your backlog lives here) | [linear.app](https://linear.app) |
| **Replit** | Code editor (afternoon: build your MVP) | [replit.com](https://replit.com) |

No coding experience required. No installs needed — everything runs in the browser.

## How It Works

The workshop follows a full agile sprint in one day. These prompts guide each phase:

**Morning — Plan**
1. Your team defines an MVP on a whiteboard (analog, no tools)
2. You photograph the whiteboard and use **Prompt 1** to turn it into Linear tickets
3. You use **Prompt 2** to prioritize, size, and add specs to your tickets
4. You assign roles (Product Owner, Developer, Copywriter) and define a sprint goal

**Afternoon — Build**
5. You connect Replit to the same Linear board
6. You use **Prompt 3** to kick off the build — Replit reads your tickets and builds features
7. You use **Prompt 4** to review what was built and learn from mistakes
8. You demo your MVP to the class

## The Prompts

| # | Prompt | When | Tool |
|---|--------|------|------|
| 01 | [Whiteboard to Linear](01-whiteboard-to-linear.md) | Morning — after whiteboard session | Claude + Linear MCP |
| 02 | [Refine Backlog](02-refine-backlog.md) | Morning — after tickets are created | Claude + Linear MCP |
| 03 | [Sprint Build Workflow](03-sprint-build.md) | Afternoon — during build sprint | Replit + Linear MCP |
| 04 | [Review & Improve](04-review-and-improve.md) | Afternoon — after building features | Any AI tool |

## Setup (we do this together in class)

**Morning (Claude + Linear):**
1. One person per team: create a Linear workspace at [linear.app](https://linear.app)
2. Invite your team members (Settings > Members > Invite)
3. Open [claude.ai](https://claude.ai) > Settings > Integrations > Connect Linear
4. Test: ask Claude "Show my Linear backlog"

**Afternoon (Replit + Linear):**
1. Open your Replit project (from Day 6, or start a new one)
2. Click Integrations (puzzle piece icon) > Connect Linear
3. Test: type `/linear Show my backlog` in the Replit Agent chat

## What is MCP?

MCP (Model Context Protocol) lets AI tools talk directly to other apps. Connect Linear to Claude, and Claude can create tickets, read your backlog, and update status — all through conversation. No copy-pasting between tools.

Today we make two connections:
- **Claude + Linear** (morning) — AI reads your whiteboard photo and creates tickets
- **Replit + Linear** (afternoon) — AI reads your tickets and builds the features

## Resources

- [Tom Blomfield / YC: Vibe Coding Best Practices](https://www.youtube.com/watch?v=BJjsfNO5JTo)
- [Zevi Arnovitz / Lenny's Podcast: Building Real Products Without Code](https://www.youtube.com/watch?v=1em64iUFt3U)

## Inspiration

This workflow is inspired by [Zevi Arnovitz's AI development process](https://www.youtube.com/watch?v=1em64iUFt3U) (PM @ Meta), where structured prompts guide AI through issue creation, planning, building, review, and documentation — enabling non-technical builders to ship production-quality products.

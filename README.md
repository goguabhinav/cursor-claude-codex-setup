# Cursor, Claude Code, Codex Setup + Cold Outreach Research

## Project Overview

This repository documents two things:

1. The setup process for installing Cursor IDE, adding the Claude Code and Codex extensions, and verifying the available login/access flows.
2. A research project on **cold outreach for B2B SaaS** — 10 practitioners, their content collected and organized, built as part of the 100Hires hiring assessment.

---

## Part 1: Tools Setup

### Tools Installed

**Cursor IDE**
- Installed from the official Cursor website.
- Opened the assignment repository/folder inside Cursor.

**Claude Code Extension**
- Installed the official Claude Code for VS Code extension by Anthropic inside Cursor.
- Extension identifier: `anthropic.claude-code`
- Version installed: `2.1.177`
- Verified that the Claude Code sidebar opened successfully inside Cursor.

**Codex Extension**
- Installed the official Codex — OpenAI's coding agent extension inside Cursor.
- Extension identifier: `openai.chatgpt`
- Version installed: `26.609.30741`
- Signed in using my ChatGPT/OpenAI account.
- Verified the setup by sending a test message and receiving a response from Codex.

---

### Setup Steps Completed

1. Created a public GitHub repository for this project.
2. Installed Cursor IDE.
3. Opened the local project folder in Cursor.
4. Opened the Extensions panel in Cursor.
5. Searched for and installed the Claude Code extension.
6. Opened the Claude Code sidebar inside Cursor.
7. Reached the Claude Code login/access screen.
8. Searched for and installed the Codex extension.
9. Opened the Codex sidebar inside Cursor.
10. Signed in to Codex using my ChatGPT/OpenAI account.
11. Tested Codex by sending a basic message and confirming that it responded.

---

### Issues Encountered and How I Solved Them

**Issue 1: Cursor initially opened in Agent/Home mode**
When I first opened Cursor, I was not in the normal editor workspace, making it difficult to find the Extensions panel.

*Solution:* Opened the proper editor window, opened the project folder, and used `Ctrl + Shift + X` to access the Extensions panel.

**Issue 2: Claude Code installation initially redirected to VS Code**
While trying to install Claude Code from the Visual Studio Marketplace, the install button opened VS Code instead of Cursor.

*Solution:* Returned to Cursor, opened the Extensions panel directly, searched for Claude Code, and installed the official Anthropic extension inside Cursor.

**Issue 3: Claude Code required a paid access path**
After installing Claude Code, the sidebar displayed login options — Claude.ai Subscription, Anthropic Console, Bedrock, Foundry, or Vertex — all of which require paid access or enterprise setup.

*Solution:* Did not purchase a subscription as the assignment did not require paid usage. Documented the access limitation and proceeded with the rest of the setup. Will get a Claude Pro subscription for any future work that requires it.

**Issue 4: Codex setup needed verification**
After installing Codex, needed to confirm whether login worked with my existing account.

*Solution:* Opened the Codex sidebar, signed in with my ChatGPT/OpenAI account, sent a test message, and confirmed that Codex responded successfully.

---

### Setup Final Status

| Item | Status |
|---|---|
| Cursor IDE installed | ✅ Completed |
| Public GitHub repository created | ✅ Completed |
| Repository opened in Cursor | ✅ Completed |
| Claude Code extension installed | ✅ Completed |
| Claude Code login/access screen reached | ✅ Completed |
| Codex extension installed | ✅ Completed |
| Codex login completed | ✅ Completed |
| Codex response verified | ✅ Completed |

---

## Part 2: Cold Outreach Research — B2B SaaS

### Research Overview

10 practitioners researched. All actively posting or publishing in 2026. Content collected across LinkedIn, YouTube, and blogs.

The filter applied throughout: if the content could not directly inform what to write or how to structure an outreach sequence, it was excluded. This is a swipe file, not a trend report.

---

### Expert Split

**Strategy experts** — systems thinkers who explain how cold outreach works end-to-end:
Roman Czerny, Suprava Sabat, Matt Lucero, Hoani Taylor, Atishay Jain

**Messaging/scripts experts** — practitioners who publish exact copy, templates, CTAs, and email teardowns you can adapt immediately:
Nick Abraham, Will Allred, Josh Braun, Jed Mahrle, Alex Berman

---

### Content Summary

| Author | Type | Files | Primary Angle |
|---|---|---|---|
| Roman Czerny | LinkedIn | 2 posts | Blueprint outreach, LinkedIn DM sequences |
| Suprava Sabat | LinkedIn | 2 posts | Trigger-based outreach, personalized PPT campaigns |
| Nick Abraham | LinkedIn | 3 posts | CTA framing, personalization tactics, campaign types |
| Atishay Jain | LinkedIn + YouTube | 1 post + 1 video | Deliverability, scaling tiers |
| Matt Lucero | YouTube | 2 videos | Copy frameworks, warm calling scripts |
| Hoani Taylor | YouTube | 2 videos | Loom outreach system, infrastructure |
| Will Allred | Blog | 3 articles | Email teardowns, personalization process |
| Josh Braun | Blog | 3 articles | Full email examples with teardowns |
| Jed Mahrle | Newsletter | 1 article | Exact CTAs, subject lines, copy patterns |
| Alex Berman | Blog | 1 article | Blueprint CTA, differentiation copy |

Total: ~20 content artifacts across 10 practitioners.

---

### Repo Structure

```
/research/sources.md                          — all source links, organized by author
/research/linkedin-posts/{author}/            — LinkedIn posts, one file per post
/research/youtube-transcripts/{author}/       — YouTube video research notes
/research/other/{author}/                     — blog posts, newsletter content
README.md
```

---

### Why These 10

Every expert included either publishes with data behind their claims (reply rates, volume metrics, case results) or shows actual email copy — not just advice about email copy. Experts who only posted GTM trends, AI tool roundups, or pipeline philosophy were excluded regardless of follower count.

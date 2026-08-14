# Storytelling — a Claude skill

Teach Claude to write like 38 master storytellers. One skill, six schools:

| Category | Who's in it |
|---|---|
| **Orators** | Barack Obama, Steve Jobs, Oprah Winfrey, Tony Robbins, Dale Carnegie, Simon Sinek |
| **Copywriters** | David Ogilvy, Gary Halbert, Eugene Schwartz, Claude Hopkins, Joseph Sugarman, Leo Burnett, Bill Bernbach, Dan Kennedy, P.T. Barnum |
| **Marketers** | Seth Godin, Donald Miller, Russell Brunson, Alex Hormozi, Robert Cialdini, Kindra Hall |
| **Screen & stage** | Walt Disney, Steven Spielberg, George Lucas, Stan Lee, Pixar (Emma Coats), Andrew Stanton |
| **Authors** | William Shakespeare, Homer, Aesop, Mark Twain, Ernest Hemingway, Stephen King, J.K. Rowling, Kurt Vonnegut |
| **Frameworks** | Matthew Dicks (Storyworthy), Nancy Duarte (Resonate), Chip & Dan Heath (Made to Stick) |

Once installed, Claude applies these techniques automatically whenever you ask it to write blog posts, LinkedIn posts, ads, sales pages, emails, speeches, brand stories, case studies, or fiction — and whenever a draft feels flat.

## Guided mode — find your unique angle

You don't need to arrive with a draft, or even an idea. Say something like *"help me tell my story"* or *"I want to post on LinkedIn but I don't know what about"*, and the skill switches into a guided experience, right inside the chat:

1. **Pick your storytelling type** from a menu — founder story, pitch, sales page, brand story, social post, case study, or fiction (or "interview me and tell me what my story is").
2. **A short interview** (two rounds max) digs for material only you have: the moment you still think about, the belief your industry gets wrong, the detail that would stop your reader mid-scroll.
3. **Three candidate angles**, each with the exact opening line it would start with. Pick one, combine two, or send Claude back.
4. **Hook first, then draft** — you approve the opening before the full piece exists.
5. **Iterate by number**: sharpen the hook, raise the stakes, change the voice to a specific master, make it more contrarian, fix the ending… until you say ship it.
6. **Leave with your angle** — a reusable one-liner that works for the next ten pieces, not just this one.

Everything happens in plain chat with numbered options — no setup, no forms, works in claude.ai and Claude Code alike.

## Install by pasting a link

### Claude Code — two commands, fully automatic

Paste into any Claude Code session:

```
/plugin marketplace add mikiarlo3/enso-AI-story-telling-skill
/plugin install storytelling@enso-skills
```

Done. The skill is installed for your user account and updates when you run `/plugin update storytelling`.

### Claude (claude.ai chat) — paste this prompt

claude.ai can't install from a URL directly, but Claude can do the work for you. Paste this into a chat (needs code execution / file analysis enabled):

> Download https://github.com/mikiarlo3/enso-AI-story-telling-skill/archive/refs/heads/main.zip , extract it, and package the folder containing SKILL.md and references/ into a single `storytelling.skill` zip file (the folder must sit at the archive root, named `storytelling`). Send me the file so I can click "Save skill".

When Claude returns the file, click **Save skill** on the card — installed.

## Install manually

### Claude (claude.ai — chat)

1. Download **[`dist/storytelling.zip`](dist/storytelling.zip)** (click, then hit the download button).
2. In Claude, open **Settings → Capabilities → Skills** (on some plans: Settings → Features).
3. Click **Upload skill** and pick the zip. Done — the skill is now available in every chat.

Ask Claude to *"write a LinkedIn post about our launch"* and watch it hook differently.

### Claude Code (terminal)

```bash
git clone https://github.com/mikiarlo3/enso-AI-story-telling-skill.git \
  ~/.claude/skills/storytelling
```

That's it — the skill loads automatically in your next session.

## How it works

- **`SKILL.md`** — the always-loaded core: a six-step writing workflow (find the moment → choose the shape → design the hook → build with stakes → land the ending → edit pass), a routing table, and an anti-pattern list.
- **`references/`** — one file per storyteller, grouped by category. Claude loads only the 1–3 files relevant to the piece it's writing (e.g. a sales page pulls Schwartz, Sugarman, and Halbert; a keynote pulls Jobs, Obama, and Duarte).
- **`references/guided-mode.md`** — the conversation protocol for guided mode: the type menu, per-type interview tracks, the three-angle pitch format, and the iteration loop.

Every reference file distills that storyteller's signature techniques in original words — what the technique is, when to use it, how to apply it to modern prose, plus a before/after example and a draft checklist. All techniques are credited to their originators; no source text is reproduced.

## Credits

This skill stands on the public teachings of the storytellers named above — their books, talks, and interviews. It began with Simon Sinek's ["How to hook your audience in 30 seconds"](https://simonsinek.com/stories/how-to-hook-your-audience-in-30-seconds-according-to-simon). Buy their books; they're all worth your time.

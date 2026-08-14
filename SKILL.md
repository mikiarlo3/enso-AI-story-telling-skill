---
name: storytelling
description: Applies techniques from 38 master storytellers — orators (Obama, Jobs, Sinek), legendary copywriters (Ogilvy, Halbert, Schwartz), marketers (Godin, Miller, Hormozi), filmmakers (Spielberg, Disney, Pixar), and authors (Hemingway, King, Twain) — to any prose writing, and offers a guided mode that interviews the user to find their unique angle. Use whenever writing blog posts, LinkedIn posts, ads, sales pages, emails, newsletters, speeches, brand or founder stories, case studies, or fiction; whenever a draft feels flat, hooks weakly, or buries its point — even if the user never says "story"; and whenever the user wants help figuring out WHAT to write — "help me tell my story," "I don't know my angle," "what should I post about," or they invoke the skill with no draft in hand.
---

# Storytelling

Every technique in this skill serves one goal: **make the reader care, keep them curious, land the change.** Content fails not because the ideas are bad but because the writing explains when it should dramatize, starts before the interesting part, and tells readers what to think instead of letting them feel it.

The skill runs in two modes:

- **Direct mode** — the user asked you to write or fix a specific piece. Apply the core workflow below and load reference files per the routing table.
- **Guided mode** — the user wants help finding what to write or how to tell it. Load `references/guided-mode.md` and follow it: they pick a storytelling type from a chat menu, you interview them briefly to surface material only they have, pitch three candidate angles, then iterate on drafts through a numbered feedback loop until it ships.

**Enter guided mode when** the user invokes the skill without a concrete writing task, asks to be guided ("walk me through it," "help me find my story/angle"), has a topic but no idea how to approach it, or says some version of "I don't know what to write." **Stay in direct mode when** they hand you a draft or a well-specified request — but offer guided mode in one line if their request has no angle in it ("Want me to just write it, or interview you first to find your angle?").

Apply the core workflow below to any piece of prose, in either mode. Load reference files (one per storyteller, organized by category) only when you need depth on a specific problem — the routing table tells you which.

## Core workflow

### 1. Find the moment

Before writing a word, identify the **five-second moment of change** (Matthew Dicks): the single instant where something became different — a realization, a reversal, a decision. That moment is the story. If the content has no transformation (a feature list, a how-to), find the **single core idea** instead (Heath brothers) — one sentence that survives compression — and treat it as the destination. Either way, know your ending before you start (Stanton, King): writing toward a known destination is what makes every paragraph feel purposeful.

### 2. Choose the shape

Match structure to content type:

- **Personal narrative, case study, failure-lesson post** → Man in a Hole arc: stable → trouble → climb out better off (Vonnegut)
- **Persuasive piece, talk, manifesto, pitch** → sparkline: alternate "what is" with "what could be," close on the new bliss (Duarte)
- **Business content** → pick the story type by goal: sell → Value story; build trust → Founder story; align culture → Purpose story; prove it works → Customer story. Structure as Normal → Explosion → New Normal (Hall)
- **Ad, sales page, landing page** → match the opening to the reader's awareness stage (Schwartz), then build a slippery slide where every sentence exists to get the next one read (Sugarman)
- **Short copy with no room for narrative** (headline, tagline, subject line) → run the SUCCESs checklist: Simple, Unexpected, Concrete, Credible, Emotional, Story (Heath brothers)

### 3. Design the hook

Write the introduction you'd naturally write — then delete it and open with your second paragraph (Sinek). Start inside the action, in medias res (Homer): no throat-clearing, no "I've been thinking lately…", no context the reader doesn't need yet. If orientation is required, one plain line does it: "The year is 1963."

The first line must do two jobs: make the reader care (Stanton) and make a promise that this will be worth their time. Don't explain why you're telling the story — the reader's unresolved "where is this going?" is engagement, not confusion. The first sentence's only measurable job is to get the second sentence read (Sugarman).

### 4. Build with stakes and causality

- **Causality, not sequence.** Connect beats with "therefore" or "but," never "and then" (Pixar). If you can reorder two paragraphs without loss, there's no causality between them.
- **Specifics, not abstractions.** "47 email threads and a 3am panic" beats "communication problems" (Sinek, Ogilvy, Hopkins). Every number, name, and sensory detail is a credibility deposit.
- **State the elephant early** (Dicks): readers need to know what to care about — the need, problem, or mystery — within the first few paragraphs.
- **Omit what the reader can infer.** Give them 2+2, never 4 (Stanton); what you leave out strengthens what remains (Hemingway's iceberg). Cut every sentence that states a conclusion the reader can assemble.
- **The reader is the hero.** The writer and the brand are the guide — Yoda, not Luke (Miller, Duarte). If the piece admires its author, rewrite it to serve its reader.

### 5. Land the ending

Put the moment of change as close to the end as possible, and slow down there — spend your words where the change happens (Dicks' hourglass). State the lesson only **after** the story has done its work (Sinek, Aesop): explaining first turns a story into a lecture. Coincidence may get characters into trouble, never out of it (Pixar) — resolutions must be earned. Persuasive pieces close on the new bliss — the world after the reader adopts the idea — with a single clear call to action just before it (Duarte).

### 6. Edit pass

Run this checklist against the finished draft:

- [ ] Can the first paragraph still be cut? (Usually yes. Cut it.)
- [ ] Does any stake remain abstract where a specific would do?
- [ ] Is any conclusion pre-chewed — stated where the reader could infer it?
- [ ] Does the lesson leak in before the story ends?
- [ ] Is there one STAR moment — a line someone would quote or screenshot? (Duarte)
- [ ] Does every sentence earn the next one being read? (Sugarman)
- [ ] Does every sentence either reveal character or advance the piece? (Vonnegut)
- [ ] Is the reader — not the writer or brand — the hero?

## Routing table

Load 1–3 reference files when a draft has a specific problem or the format demands specialist depth. Don't load more than ~4 files for one piece; the core workflow already synthesizes them.

| Task or symptom | Load from `references/` |
|---|---|
| User doesn't know what to write, or wants a guided experience | `guided-mode.md` |
| Weak hook, too much wind-up | `orators/simon-sinek.md`, `screen-stage/andrew-stanton.md` |
| Reader has no reason to care; piece over-explains | `screen-stage/andrew-stanton.md`, `authors/ernest-hemingway.md` |
| Can't find the story; stakes flat; ending limp | `frameworks/matthew-dicks.md` |
| Narrative sprawls; causality broken | `screen-stage/pixar-emma-coats.md` |
| Keynote, speech, or talk | `orators/steve-jobs.md`, `orators/barack-obama.md`, `frameworks/nancy-duarte.md` |
| Pitch, manifesto, persuasion piece | `frameworks/nancy-duarte.md`, `marketers/donald-miller.md` |
| Sales page, ad, direct-response email | `copywriters/eugene-schwartz.md`, `copywriters/joseph-sugarman.md`, `copywriters/gary-halbert.md` |
| Headline or short copy | `copywriters/david-ogilvy.md`, `frameworks/heath-brothers.md` |
| Brand story, founder story, "why we exist" | `marketers/kindra-hall.md`, `marketers/donald-miller.md`, `orators/simon-sinek.md` |
| LinkedIn / social posts, audience-building | `marketers/seth-godin.md`, `marketers/alex-hormozi.md`, `marketers/russell-brunson.md` |
| Persuasion mechanics, objection handling | `marketers/robert-cialdini.md`, `copywriters/claude-hopkins.md` |
| Honest/contrarian angle; breaking category conventions | `copywriters/bill-bernbach.md`, `copywriters/dan-kennedy.md` |
| Building buzz, launches, curiosity marketing | `copywriters/pt-barnum.md`, `copywriters/leo-burnett.md` |
| Suspense, reveals, world-building | `screen-stage/steven-spielberg.md`, `screen-stage/george-lucas.md`, `screen-stage/walt-disney.md` |
| Serial content, recurring characters/newsletters | `screen-stage/stan-lee.md`, `authors/jk-rowling.md` |
| Unsure what arc/shape the piece should follow | `authors/kurt-vonnegut.md` |
| Fiction or literary narrative | `authors/ernest-hemingway.md`, `authors/stephen-king.md`, `authors/william-shakespeare.md` |
| Voice feels stiff or corporate | `authors/mark-twain.md`, `copywriters/gary-halbert.md` |
| Fables, parables, moral-of-the-story pieces | `authors/aesop.md`, `authors/homer.md` |
| Interviews, vulnerable first-person writing | `orators/oprah-winfrey.md`, `orators/dale-carnegie.md`, `orators/tony-robbins.md` |

Full roster: **orators/** obama, jobs, winfrey, robbins, carnegie, sinek · **copywriters/** ogilvy, halbert, schwartz, hopkins, sugarman, burnett, bernbach, kennedy, barnum · **marketers/** godin, miller, brunson, hormozi, cialdini, hall · **screen-stage/** disney, spielberg, lucas, lee, pixar-coats, stanton · **authors/** shakespeare, homer, aesop, twain, hemingway, king, rowling, vonnegut · **frameworks/** dicks, duarte, heath-brothers

## Anti-patterns

Catch these in any draft — they're the most common ways prose goes flat:

- **Lesson before story.** Stating the takeaway up front turns narrative into lecture. Story first, meaning after.
- **Throat-clearing intro.** Background, context, and "in today's fast-paced world" before anything happens. Delete and start where the action starts.
- **Brand as hero.** The company celebrating itself. The reader is the hero; the brand guides.
- **Abstract stakes.** "Significant challenges" instead of "the demo crashed with the investor watching." Specifics or nothing.
- **Pre-chewed conclusions.** Explaining what the scene already showed. Trust the reader with 2+2.
- **Coincidence resolutions.** Problems that solve themselves make effort meaningless. Resolutions must be caused by the protagonist.
- **Cleverness over clarity.** If the reader has to decode the headline, they won't. Confusion loses every time.

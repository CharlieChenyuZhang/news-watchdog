# Daily brief search space (news-watchdog)

Audience: Bay Area tech startup founder (Chenyu). Goal: high-signal daily update, not a firehose.
Cadence: every day 7:00 AM PT. Prefer last ~24h; mark older items. Every item needs a primary source link.
Always open with TLDR (3–5 bullets). Quiet categories: write “nothing material” — don’t invent filler.
Also run **G keywords**, **H discourse**, **I pre-launch/early-signal radar**, and **J trends/topics/directions** every day (complement to direct site checks).
**Priority #2 for the reader:** a short judgmental summary of *what directions are hot* (LLM / agents / AI agency / safety / infra / …) — topics, keywords, what’s heating up next month vs next year — not just a news dump.
**Priority #1 for the reader:** do not miss high-signal “everyone is talking about this” items (builder Twitter/X, HN, lab Discord/Slack echoes via public posts). Freshness windows below.

## A. Frontier labs — official content + events

Scan each org’s news/blog/research + event pages / Luma for new posts, model cards, product drops, hiring-from-events, Bay Area events.

| Org | Primary content URLs to check | Events / notes |
|-----|-------------------------------|----------------|
| OpenAI | openai.com/index, openai.com/blog, openai.com/news, openai.com/research | DevDay, Exchanges; lu.ma OpenAI |
| Anthropic | anthropic.com/news, anthropic.com/research, anthropic.com/institute | SF events / partners |
| Google DeepMind / Google AI | deepmind.google/discover/blog, institute.deepmind.com, blog.google (AI), ai.google.dev | Build with Gemini, Cloud AI events |
| Microsoft AI / MAI | microsoft.ai/news, blogs.microsoft.com/ai | Ignite / Build AI tracks |
| Meta AI / FAIR | ai.meta.com/blog, research.meta.ai/blog, about.fb.com/news | Meta events |
| xAI | x.ai (blog/news) | Separate from SpaceX |
| SpaceX | spacex.com (only AI/compute/Starlink-relevant) | Rare; skip fluff |
| Amazon / AWS AI | aws.amazon.com/blogs/machine-learning, amazon.science | re:Invent season |
| Apple ML / Intelligence | machinelearning.apple.com, apple.com/newsroom (AI only) | WWDC aftermath |
| Mistral | mistral.ai/news | EU frontier signal |
| Cohere | cohere.com/blog | Enterprise LLM |
| SSI / Safe Superintelligence | press + reputable coverage | Ilya-led; sparse official |
| Thinking Machines Lab | press + reputable coverage | Mira-led; sparse official |
| Perplexity | perplexity.ai/hub or blog | Consumer AI |
| Midjourney / Runway / ElevenLabs | official blogs | Generative apps layer |
| DeepSeek / Moonshot / Zhipu / Qwen (Alibaba) / ByteDance Seed | official EN blogs when available | Competitive frontier; EN primary preferred |
| NVIDIA | blogs.nvidia.com (AI/compute) | Infra constraint signal |
| CoreWeave / major neoclouds | blogs when material | Capex / availability |

Also search Luma + AI Week SF calendars for lab-hosted or lab-speaker events in SF/Bay Area.

## B. Top incubators / accelerators — applications + events

Flag: newly opened apps, deadlines ≤30 days, Demo Days, info sessions.

| Program | Apply / hub |
|---------|-------------|
| Y Combinator | ycombinator.com/apply |
| a16z Speedrun | speedrun.a16z.com |
| Plug and Play | plugandplaytechcenter.com (by vertical) |
| Google for Startups Accelerator | startup.google.com |
| Techstars (incl. Anywhere) | techstars.com |
| Sequoia Arc | sequoiacap.com/arc |
| Neo Residency | neo.com / Neo news |
| Endless Frontier Labs | endlessfrontierlabs.com |
| 500 Global | 500.co |
| Alchemist | alchemistaccelerator.com |
| South Park Commons | southparkcommons.com |
| HF0 | hf0.com |
| Entrepreneur First (US / Bridge SF / regional) | joinef.com |
| Microsoft for Startups | microsoft.com/startups |
| Founders Inc | foundersinc.com |
| On Deck / ODF | beondeck.com |
| PearX | pear.vc |
| Antler | antler.co |
| Creative Destruction Lab | creativedestructionlab.com |

## C. News wires & high-signal outlets (scan headlines, then primary)

Reuters, Bloomberg, FT, WSJ (Tech), TechCrunch, The Information (if accessible), Semafor, The Verge (AI), Wired, Ars Technica, MIT Tech Review, Rest of World (global), Platformer / Stratechery (when AI-strategic).

## D. Papers & technical discourse

- arXiv cs.AI / cs.CL / cs.LG — last 24–48h; prefer agents, evals, efficiency, safety
- Hugging Face Daily Papers / trending
- Notable conference CFPs or results (NeurIPS, ICML, ICLR, ACL) when timely
- X/Twitter: use *sourced reporting* of posts by lab CEOs/research leads + reputable quote coverage (don’t invent screenshots)

## E. Capital, talent, infra (founder-relevant only)

- Large AI rounds, acquihires, lab IPO/secondary rumors with named sources
- NVIDIA / cloud GPU capacity & pricing moves
- Policy: US/EU/CA/China frontier rules, export controls, safety standards bodies

## F. Bay Area events calendar

Always refresh: AI Week SF, OpenAI DevDay, The AI Conference, SF Tech Week, Disrupt, Assembling, Google/Microsoft/local lab workshops, high-signal Luma (founder dinners, demo nights). Include date, venue, why go, link.


## G. Keyword search (catch what site crawls miss)

Run these queries every day via the built-in web search tool (see “Search engine” below). Prefer results from the last 24–48 hours; open promising hits with WebFetch and cite the primary page.

### Standing query pack (rotate / adapt date)

**Labs & products**
- `OpenAI OR Anthropic OR "Google DeepMind" OR "xAI" OR Mistral announce OR launch OR release 2026`
- `"GPT" OR Claude OR Gemini OR Grok OR "Muse Spark" model (launch OR release OR preview) 2026`
- `OpenAI DevDay OR "Build with Gemini" OR "AI Conference" OR "SF Tech Week" 2026`

**Safety / policy / RSI**
- `"pace the frontier" OR "R&D Automation" OR "model misalignment" OR "frontier AI" standards OR evaluator 2026`
- `AI export control OR "chip ban" OR "AI safety" regulation US OR EU OR California 2026`

**Papers & agents**
- `site:arxiv.org agent OR LLM OR "tool use" OR verifier 2026` (or arXiv API / HF Daily Papers)
- `"Hugging Face" "daily papers" AI`

**Capital / infra**
- `(OpenAI OR Anthropic OR "xAI" OR Mistral OR Perplexity) (funding OR raises OR IPO OR secondary) 2026`
- `NVIDIA OR CoreWeave OR "GPU cloud" (shortage OR capacity OR pricing) AI 2026`

**Incubators**
- `"Y Combinator" OR "a16z Speedrun" OR "Plug and Play" OR "Sequoia Arc" OR "Neo Residency" (apply OR deadline OR "Demo Day") 2026`
- `"Google for Startups" OR Techstars OR "Entrepreneur First" accelerator (application OR deadline) 2026`

**Bay Area events**
- `San Francisco OR "Bay Area" (AI OR LLM OR "startup") (meetup OR demo OR hackathon OR mixer) (Luma OR "lu.ma") 2026`
- `site:lu.ma OpenAI OR Anthropic OR "a16z" OR YC San Francisco`

### How to use keyword hits
1. Site crawl (A–F) is the spine; keyword search is the net for leaks, exclusives, and pages not on the watchlist.
2. Deduplicate against site crawl and against yesterday’s brief; don’t double-count the same announcement. Prefer **delta-only** continuity (what changed since yesterday), not a full rehash.
3. If search returns nothing useful, say so — don’t pad from stale SEO farms.
4. Paywalled exclusives: cite the outlet + date; note if full text wasn’t readable.

## Search engine (how this bot searches)

- Primary: Cursor / Grok Bot **built-in WebSearch** — queries an **external web search index** (not a hand-picked “I open Google Chrome and type” workflow). Some sites block or throttle that index, so empty/stale hits ≠ “doesn’t exist.”
- Direct pages: **WebFetch** / HTTP fetch of known URLs (lab blogs, apply pages, arXiv).
- Fallback when search/fetch fail: box **browser** for the live page, or `gh`/API for GitHub-hosted material.
- Not used as the daily spine: random social scrapes without a citable URL.


## H. Builder / viral discourse (PRIORITY — “what is everyone talking about?”)

This section is **as important as lab official blogs**. Chenyu explicitly does not want to miss high-signal social/builder discourse (e.g. TypeSafe Jev).

### Every run — required
1. **Hacker News** — front page + top AI/Show HN (last 24–48h). Open threads that look founder-relevant (≥~100–200 points or clearly viral).
2. **Discourse keyword pack**
   - `TypeSafe OR Jev OR "System One" OR "Diogo Almeida" AI OR LLM 2026`
   - `(Hacker News OR "Show HN" OR "Product Hunt") (AI OR LLM OR agent) (launch OR introduce) 2026`
   - `"everyone is talking" OR viral OR "blew up" (AI OR LLM OR agent) (launch OR model) 2026` (use judiciously; verify)
   - Trending builder topics of the week (agents, decision models, evals, voice, computer-use, etc.)
3. **Named watchlist (grow when user flags a miss):** TypeSafe / Jev / Diogo Almeida; add new names the same day the user mentions them.

### Time windows (label each item)
| Window | What to include |
|--------|-----------------|
| **Last 24h** | Breaking launches, exclusives, new posts |
| **This week** | Still-hot threads, follow-up essays, Gateway listings, second-wave reactions |
| **~30 days** | Major launches/discourse the brief never covered, or that still shape founder strategy |
| **Up to ~6 months** | Only if **high signal + still referenced** OR **never appeared in prior briefs** — one short “catch-up” or “still foundational” bullet with original date, not a full rehash |

### Rules
- **First-time in this repo’s briefs → include**, even if the launch was weeks ago (mark date; keep short).
- **Already covered yesterday → delta only** (new metrics, rebuttals, distribution, enterprise uptake) or skip.
- Prefer primary launch posts + strong secondary (HN, Register, DEV, company blog). No rumor without a URL.
- Put the hottest discourse items in **TLDR** when founders would feel behind for missing them.



## I. Pre-launch / early-signal radar (stay ahead of launches like Jev)

Goal: surface **leading indicators** weeks/months before a public launch so Chenyu can try early access, prototype against the idea, or reach out — not discover the product on launch day.

### What counts as an early signal (include when sourced)
1. **Talent moves** — frontier-lab researchers/engineers leaving to found or join stealth (OpenAI, Anthropic, DeepMind, Meta FAIR, SSI, Thinking Machines, xAI, Google Brain alumni, etc.).
2. **Stealth / seed financing** — named raises, SAFE filings chatter with reputable outlets, “ex-OpenAI raises $Xm for …”
3. **Hiring & careers pages** — new stealth companies hiring for “decision models,” “agent control plane,” “RLHF,” “calibra*,” infra; unusual job spikes.
4. **Early access / waitlists / Gateway listings** — API waitlists, “coming to AI Gateway,” closed betas, Design Partner calls.
5. **Talks / papers / vague teases** — conference talks, arXiv from known names, “building something new” threads that aren’t vapor.
6. **Warm intros / reach-out hooks** — when signal is strong, note *who* to contact (founder LinkedIn/X, apply@, waitlist URL) in one line.

### Every-run keyword / source pack
- `(ex-OpenAI OR "former OpenAI" OR "left OpenAI" OR "ex-Anthropic" OR "former DeepMind") (founder OR founding OR stealth OR raises OR seed) 2026`
- `(stealth OR "exited stealth" OR waitlist OR "early access" OR "design partner") (AI OR LLM OR agent) (startup OR lab) 2026`
- `"raising" OR "raised" OR "seed round" OR "Series A" (AI OR LLM) ("ex-OpenAI" OR Anthropic OR DeepMind) 2026`
- Watch outlets strong on talent/stealth: The Information, Bloomberg, Reuters, TechCrunch, Fortune, Register, Soft-ish Builder Twitter via search (verify before citing).
- Scan “who left labs this month” style roundups when they appear.

### Confidence labels (required on early signals)
- **Confirmed** — primary filing, company blog, named reputable outlet
- **Likely** — multiple secondary sources aligned
- **Rumor** — single thin source; say so; do not treat as fact
Never invent a stealth company. Prefer “watch this person/theme” over fake specificity.

### Output placement
- Hot early signals → **TLDR** + short **Early signals / stealth radar** section
- Include: who, from where, what they’re building (if known), money if known, **how to get closer** (waitlist / email / X), date of signal
- Dedupe: once covered, only deltas (closed raise, exited stealth, GA launch)



## J. Trends / topics / directions (PRIORITY #2 — “what’s the meta?”)

Goal: every day, give Chenyu a **synthesis** of where AI / LLM / agents / “AI agency” discourse is pointing — not another news list. Answer: what’s hot *now*, which **topics/keywords** keep recurring, and what looks likely to heat up **next ~month** and **next ~year**. Example signal he care about: a friend saying “AI safety is getting hotter” should show up here with evidence and a call on whether that’s ambient chatter or capital/talent shifting.

### Every run — required synthesis
1. Scan today’s hits from A–I (labs, papers, HN, capital, policy, early signals) and extract **themes**, not headlines.
2. Run a light **topics keyword pack** (adapt; don’t invent fake virality):
   - `(AI OR LLM OR agent OR "AI agent" OR agency) (trend OR thesis OR "everyone is" OR discourse OR narrative) 2026`
   - `"AI safety" OR alignment OR evals OR "model spec" OR "responsible scaling" OR "AI governance" 2026`
   - `(agent OR "computer use" OR "tool use" OR "decision model" OR "System One" OR orchestrator OR "agent substrate") (startup OR open-source OR infra) 2026`
   - `(coding agent OR "AI IDE" OR "software engineer" agent OR SWE-bench) 2026`
   - `(robotics OR "world model" OR "video model" OR multimodal) (frontier OR lab) 2026`
   - `(inference OR "GPU" OR "AI infra" OR neocloud OR "open weights") (shortage OR pricing OR capacity) 2026`
3. Cross-check: HN front-page themes, HF Daily Papers clusters, lab blogs, policy/safety standards bodies, VC thesis posts (only when sourced).

### Output format (place **immediately after TLDR** — second section in the brief)
Use a short section titled **Trends / topics / directions** with:

| Horizon | What to write |
|---------|----------------|
| **Hot now (this week)** | 3–6 topics with 1-line why + 1–2 example links/keywords |
| **Rising (~next month)** | 2–4 bets that look like they’re accelerating (hiring, papers, OSS, capital) |
| **Longer bet (~next year)** | 1–3 structural directions (still speculative — label judgment) |
| **Keywords to watch** | Compact tag list (e.g. `AI safety`, `decision models`, `agent substrate`, `RSI tooling`) |
| **Founder take** | 2–4 sentences: what to build against / ignore / dig into this week |

### Rules
- **Judgment required** — say what’s loud vs what’s real (volume ≠ capital ≠ product traction). Mark confidence: **Hot** / **Rising** / **Watch** / **Fading**.
- Delta-first vs yesterday’s Trends section: if the meta didn’t move, say “meta stable; …” in one line — don’t rewrite the same essay.
- Tie claims to evidence from this brief’s sources (HN pts, papers, raises, policy). No vibe-only paragraphs.
- Include AI safety / governance when discourse or policy moves — even if labs are quiet — because founders need the narrative early.
- Quiet day: still write the section; shorter is fine.

## Output rules

0. **Discourse is a first-class output.** If HN/X/builders are loudly discussing something founder-relevant and it is new to our briefs or still hot, it belongs in TLDR — even if no frontier lab blogged it today.
0b. **Trends / topics / directions is Priority #2.** Immediately after TLDR, synthesize hot / rising / next-year directions + keywords + a short founder take (section J). Do not bury this at the bottom.

1. TLDR first (include urgent app deadlines + one meta bullet when the discourse shift is big).
2. Section order: **Trends / topics / directions** → Early signals / stealth radar → Lab site updates → Lab/Luma events → Incubator apps & events → News/products → Papers/discourse → Bay Area events.
3. Prefer primary sources; skip rumor without sourcing.
4. Deduplicate vs yesterday’s brief; only carry forward with material updates.
5. Publish `briefs/YYYY-MM-DD.md` to main on CharlieChenyuZhang/news-watchdog via `gh` Contents API.
6. User notify: link + TLDR + **trends callouts** + early-signal callouts + open apps/deadlines.

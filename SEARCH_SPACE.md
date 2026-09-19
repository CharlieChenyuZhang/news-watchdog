# Daily brief search space (news-watchdog)

Audience: Bay Area tech startup founder (Chenyu). Goal: high-signal daily update, not a firehose.
Cadence: every day 7:00 AM PT. Prefer last ~24h; mark older items. Every item needs a primary source link.
Always open with TLDR (3–5 bullets). Quiet categories: write “nothing material” — don’t invent filler.
Also run **section G keyword searches** every day (complement to direct site checks).

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
2. Deduplicate against site crawl; don’t double-count the same announcement.
3. If search returns nothing useful, say so — don’t pad from stale SEO farms.
4. Paywalled exclusives: cite the outlet + date; note if full text wasn’t readable.

## Search engine (how this bot searches)

- Primary: Cursor / Grok Bot **built-in WebSearch** — queries an **external web search index** (not a hand-picked “I open Google Chrome and type” workflow). Some sites block or throttle that index, so empty/stale hits ≠ “doesn’t exist.”
- Direct pages: **WebFetch** / HTTP fetch of known URLs (lab blogs, apply pages, arXiv).
- Fallback when search/fetch fail: box **browser** for the live page, or `gh`/API for GitHub-hosted material.
- Not used as the daily spine: random social scrapes without a citable URL.

## Output rules

1. TLDR first (include urgent app deadlines).
2. Sections: Lab site updates → Lab/Luma events → Incubator apps & events → News/products → Papers/discourse → Trends → Bay Area events.
3. Prefer primary sources; skip rumor without sourcing.
4. Deduplicate vs yesterday’s brief; only carry forward with material updates.
5. Publish `briefs/YYYY-MM-DD.md` to main on CharlieChenyuZhang/news-watchdog via `gh` Contents API.

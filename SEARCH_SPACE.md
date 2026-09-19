# Daily brief search space (news-watchdog)

Audience: Bay Area tech startup founder (Chenyu). Goal: high-signal daily update, not a firehose.
Cadence: every day 7:00 AM PT. Prefer last ~24h; mark older items. Every item needs a primary source link.
Always open with TLDR (3–5 bullets). Quiet categories: write “nothing material” — don’t invent filler.

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

## Output rules

1. TLDR first (include urgent app deadlines).
2. Sections: Lab site updates → Lab/Luma events → Incubator apps & events → News/products → Papers/discourse → Trends → Bay Area events.
3. Prefer primary sources; skip rumor without sourcing.
4. Deduplicate vs yesterday’s brief; only carry forward with material updates.
5. Publish `briefs/YYYY-MM-DD.md` to main on CharlieChenyuZhang/news-watchdog via `gh` Contents API.

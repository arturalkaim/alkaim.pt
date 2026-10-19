# Artur Alkaim
## Software Engineer · Lisbon

Content source for alkaim.pt (index.html). Keep in sync when editing the page.
Page copy uses no em dashes (see the artur-voice skill).

### Positioning
Person-first: engineer in Lisbon, Nezasa mentioned but not the headline.
Design direction: "Phosphor" — terminal/monospace, dark-only, amber + cyan on blue-black.

### Hero
Software engineer in Lisbon. Ten years across Scala, TypeScript, and the
infrastructure underneath. Currently squad tech lead at Nezasa, teaching
LLM agents to do real engineering work without breaking prod, and getting
engineers to actually work with them.

### Now
- Dad first: raising a three-year-old, with a second boy on the way
- Agentic dev tooling: building review pipelines, verification harnesses, and workflow orchestration on top of LLMs, and helping developers bring AI into their day-to-day
- Squad tech lead at Nezasa: payments, sourcing, and infrastructure for TripBuilder
- Mentoring engineers · devops & on-call rotation

### Work (ls ~/work)
- **tripbuilder/** — Real-time personalised travel planning & booking. Payment-provider
  integrations and platform scale, with hundreds of features shipped while the company tripled.
  Scala · TS · MongoDB · AWS. (nezasa · 2018→)
- **evalmy.page** — Landing-page evaluator that scores pages on human conversion and
  on how well AI assistants like ChatGPT, Claude and Perplexity can find them, with LLM-powered
  headline & CTA rewrites. Next.js · Supabase · Playwright · Polar payments · Vercel. (● live)
- **quintas/** (https://github.com/arturalkaim/quintas, engine repo only; game URLs stay private) —
  Pixel-art platform games that tell a kid's life story, one level per year, with a birthday
  cake after each. One engine, one file per kid, shared leaderboard, frame-hash regression tests.
  JS · canvas. The games themselves are for the kids, not for the internet. (for the kids)
- **brandbassador/** — Led iOS + Android development for an international
  ambassador-marketing platform. Ionic · Angular · Node. (syone · 2016–18)
- **archive/** — reddal.gg (esports ladders; React · Node · MongoDB), beautify.pt, where-to-eat, and other retired experiments.

### Contact
- Email: artur@alkaim.pt (Cloudflare Email Routing → Gmail)
- GitHub: https://github.com/arturalkaim
- LinkedIn: https://www.linkedin.com/in/arturalkaim/
- X: https://x.com/arturalkaim
- Instagram: https://instagram.com/arturalkaim

### Career timeline (reference, not all on page)
- 2018–now: Nezasa — Senior SWE → squad tech lead. TripBuilder, payments, sourcing, infra, mentoring, on-call.
- 2016–2018: Syone — IT Consultant. Brandbassador 1.0 support; led Brandbassador 2.0 mobile (Ionic/Angular/TS), backend Node.js/Hapi/Couchbase.
- Education: MSc + BSc Information Systems & Software Engineering, Técnico Lisboa; semester at University of Amsterdam.

### Writing (ls ~/writing)
Posts live at writing/<slug>.html, served at https://alkaim.pt/writing/<slug>.
To publish: copy templates/post.html (not deployed), fill the {{…}} placeholders,
write the body in <article>, then add a row (newest first) to the "ls ~/writing"
list in index.html, and add an <item> to feed.xml
(newest first, bump lastBuildDate). Drafts can be .md — .assetsignore keeps *.md and templates/
off the site.

Posts:
- 2026-10-19 · The lazy way to AI (/writing/the-lazy-way-to-ai)
- 2026-10-19 — Hello (/writing/hello)

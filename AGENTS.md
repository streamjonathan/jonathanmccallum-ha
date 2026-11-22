# AGENTS.md — jonathanmccallum-ha (Hausa mirror of jonathanmccallum.com)

Hausa mirror site. Same theme and design as the main site (Paper Light),
content translated into Hausa, meaning-first. Repo: streamjonathan/jonathanmccallum-ha.
Live (when approved): ha.jonathanmccallum.com. Proof: jonathanmccallum-ha.pages.dev.

## Mission

Mirror jonathanmccallum.com in Hausa — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## The one rule above all

**Never publish or alter live production assets without Jonathan's clear
permission.** The Hausa site goes live on ha.jonathanmccallum.com only when
he says so, after reading the pilot article(s). Drafts stay drafts until he
approves them. Work on a branch, never straight on main. Give Bobby a preview URL.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Lewis quotations: use the published Hausa translation where one exists
  (cite it); otherwise translate fresh and mark it "translated for this site".
- Bible verses: use the Littafi Mai Tsarki wording, never re-translate from the English article. No direct verse quotations appear in the 5 proof articles; the exact Littafi Mai Tsarki wording of John 6:35 and John 4:14 was not verified — check against the printed Littafi Mai Tsarki before quoting any verse directly.
- Names (never vary): Yesu, Allah, Aslan, Narnia, Lucy, Digory, Tirian, Adamu da Hauwa'u, Bitrus. Book titles are kept in English (The Chronicles of Narnia, The Magician's Nephew, The Great Divorce, The Space Trilogy, The Last Battle) — flagged for Jonathan, as no published Hausa translation was found.
- Voice: Warm, plain, short sentences, no preaching. Direct address uses masculine singular 'kai' as the generic form (flagged). Orthography: Boko (Latin script) with ɓ, ɗ, ƙ, ’y.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.

# as-sur-how-it-works

A single-page explainer for **AS-Sur**, the WhatsApp bot that answers the Physicianeers
2026 cohort's logistics questions from their
[hub](https://mtc-qa-hub.vercel.app/) — and says so plainly when the hub does not cover
the question.

**Read it:** https://gegesay89.github.io/as-sur-how-it-works/

Written for doctors learning AI rather than for software engineers: what the bot does, how
students summon it, the four parts it is built from, three short code snippets, and the
engineering lessons worth passing on — including why it has no vector database, why
real-time listeners came out both cheaper and fresher than polling, and why refusing to
answer is a feature.

This repo is the explainer, not the bot. There is no build step and no dependencies:
`index.html` is the whole site.

- [`index.html`](index.html) — the page
- [`announcement.md`](announcement.md) — the short message shared in the student groups

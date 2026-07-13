# SearchSteward

**A job-search radar that watches company career pages for you.**

Instead of scrolling job boards, SearchSteward monitors **40,000+ company
career pages** directly and scores every new opening against your résumé the
day it's posted — so well-matched roles find you, not the other way around.

- 🌐 **[searchsteward.com](https://searchsteward.com)** — the product
- 🔍 **[Résumé ↔ JD Matcher](https://searchsteward.com/tools/resume-match)** — free, no signup, runs in your browser
- 👻 **[Ghost Job Detector](https://searchsteward.com/tools/ghost-job-checker)** — check a posting for scam/ghost signals

## Open source

We publish the pieces where transparency *is* the feature — see
[**searchsteward/searchsteward**](https://github.com/SearchSteward/searchsteward):

- `resume-match/` — the exact TypeScript behind our free matcher and ghost-job
  checker. Zero dependencies; publishing it backs up the "your résumé never
  leaves the page" claim.
- `ghost-signal/` — the production Python module behind the in-app ghost-job
  badge, with every signal and weight documented.

_Built for active job seekers who want signal over noise._

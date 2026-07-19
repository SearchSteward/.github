# SearchSteward

**A job-search radar that watches company career pages for you.**

Instead of scrolling job boards, SearchSteward monitors **40,000+ company
career pages** directly and scores every new opening against your résumé the
day it's posted — so well-matched roles find you, not the other way around.

- 🌐 **[searchsteward.com](https://searchsteward.com)** — the product
- 🔍 **[Résumé ↔ JD Matcher](https://searchsteward.com/tools/resume-match)** — free, no signup, runs in your browser
- 👻 **[Ghost Job Detector](https://searchsteward.com/tools/ghost-job-checker)** — check a posting for scam/ghost signals
- 📘 **[Getting Started guide](https://searchsteward.com/guides/getting-started)** — signup to first scored matches, step by step

## Open source

We publish the pieces where transparency *is* the feature — the code that
reads, checks, and classifies job postings on your behalf. Each library is
MIT-licensed, dependency-free, tested in CI, and the same code running in
production:

- **[resume-match](https://github.com/searchsteward/resume-match)** (TypeScript) —
  the exact code behind our free matcher and ghost-job checker. Runs entirely
  in your browser; publishing it backs up the "your résumé never leaves the
  page" claim.
- **[ghost-signal](https://github.com/searchsteward/ghost-signal)** (Python) —
  the production module behind the in-app ghost-job badge, with every signal
  and weight documented.
- **[salary-parser](https://github.com/searchsteward/salary-parser)** (Python) —
  extracts real salaries from posting text without fabricating them
  (*"10-15 hours per week"* is not a $20,800 salary).
- **[location-parser](https://github.com/searchsteward/location-parser)** (Python) —
  parses the location strings job boards actually emit, corruption and all.

Product tour and architecture overview:
[**searchsteward/searchsteward**](https://github.com/searchsteward/searchsteward).

_Built for active job seekers who want signal over noise._

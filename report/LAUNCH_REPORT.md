# Buyer Arena: launch readiness

**Launch readiness: 95/100 · ★★★★★ (5/5)**

> 40 synthetic participants across 5 panels · standard depth · 1 min

| Panel | % | ★ | Attention |
|---|---:|---|---:|
| End users | 100 | ★★★★★ | 40% |
| Developers | 100 | ★★★★★ | 15% |
| Investors | 83 | ★★★★☆ | 15% |
| Red team | 94 | ★★★★½ | 15% |
| Segments | 91 | ★★★★½ | 15% |

## End users — 100/100 ★★★★★

_Do customers reach the goal, and where are they lost?_

| Checks | % | ★ | What to do: |
|---|---:|---|---|
| Goal completion | 100 | ★★★★★ | Start with the top friction in the End users tab. |
| Price is findable | 100 | ★★★★★ | Put pricing in the navigation and near the main button. |
| Clear way to start | 100 | ★★★★★ | Use one explicit primary button above the fold. |
| No browser errors | 100 | ★★★★★ | Fix the errors listed under Engineering in the End users tab. |
| Low friction | 100 | ★★★★★ | Remove loops, pop-ups and form rejections. |
| Short path to the goal | 100 | ★★★★★ | Remove pages and fields between landing and first value. |

## Developers — 100/100 ★★★★★

_Can a developer get it running from the README?_

| Checks | % | ★ | What to do: |
|---|---:|---|---|
| README that explains and onboards | 100 | ★★★★★ | Add a quick-start section with exact commands and one screenshot of the result. |
| Quick-start commands work | 100 | ★★★★★ | Make every README command match a real script, in the order a newcomer runs them. |
| Prerequisites are stated | 100 | ★★★★★ | State the runtime version in the README, package.json engines and .nvmrc. |
| CI runs the tests | 100 | ★★★★★ | Add a CI workflow that installs and runs the tests on every push. |
| Automated tests exist | 100 | ★★★★★ | Cover the main path with automated tests before inviting contributors. |
| Contributor documentation | 100 | ★★★★★ | Add CONTRIBUTING, SECURITY and a CHANGELOG. |
| Clear licence | 100 | ★★★★★ | Add a standard licence file (Apache-2.0 or MIT for adoption). |
| Quality tooling | 100 | ★★★★★ | Enable strict types, a linter and a formatter, and ship an examples folder. |
| Clean install succeeds | 100 | ★★★★★ | Make a clean install pass with the lockfile only (npm ci). |
| Build succeeds | 100 | ★★★★★ | Fix the build so it passes on a clean machine. |
| Time to first success | 100 | ★★★★★ | Offer one command that shows a real result in under a minute. |

## Investors — 83/100 ★★★★☆

_What can an investor verify about value and business model?_

**Best-supported business model:** Open core · Virality potential: 100/100

| Checks | % | ★ | What to do: |
|---|---:|---|---|
| Problem and promise are clear | 100 | ★★★★★ | Open the README with one sentence of value and a short “Why” section. |
| Differentiation is explicit | 85 | ★★★★½ | Add a “vs alternatives” table that shows what only you do. |
| Demo and visual proof | 100 | ★★★★★ | Show a one-command demo and a screenshot or GIF above the fold. |
| Business model is articulated | 100 | ★★★★★ | Write down who pays, for what, and why the free part leads there. |
| Licence fits the model | 95 | ★★★★★ | Pick a licence that serves adoption and keeps the paid layer separate. |
| Proof of execution | 92 | ★★★★½ | Show steady execution: tests, CI, releases and a changelog. |
| Adoption evidence | 5 | ½☆☆☆☆ | Get real users before fundraising: publish a release, list adopters and collect two or three testimonials. |
| Defensibility | 100 | ★★★★★ | Explain what gets better with usage (data, calibration, integrations). |
| Target market is clear | 90 | ★★★★½ | Name the first customer segment and the job it pays you to do. |
| Honest limits and risks | 100 | ★★★★★ | State limitations plainly; investors trust what is honest. |
| Open-source governance | 100 | ★★★★★ | Add governance files so companies can adopt and contribute safely. |

## Red team — 94/100 ★★★★½

_How exposed is it, including to AI agents?_

**Risk index:** 6/100 (Low risk) · **AI-agent risk:** 5/100

| Checks | % | ★ | What to do: |
|---|---:|---|---|
| No secrets in the repository | 100 | ★★★★★ | Revoke any exposed key, remove it from history and add secret scanning to CI. |
| No known-vulnerable dependencies | 100 | ★★★★★ | Update or replace the vulnerable packages. |
| No code runs on install | 100 | ★★★★★ | Avoid install hooks; move setup to an explicit command. |
| CI is hardened | 100 | ★★★★★ | Pass inputs through env variables, declare least-privilege permissions, pin actions. |
| No prompt injection in files agents read | 100 | ★★★★★ | Remove hidden Unicode and imperative instructions aimed at AI from docs, skills and prompts. |
| MCP tools are least-privilege | 100 | ★★★★★ | Give MCP tools narrow inputs, allow-lists and no shell; keep descriptions free of instructions. |
| No over-broad agent permissions | 100 | ★★★★★ | Never recommend skipping permissions; ship scoped settings and signed installers. |
| Model output is validated | 80 | ★★★★☆ | Treat web content as data: validate every model answer against a schema before acting. |
| Limited shell execution | 76 | ★★★★☆ | Avoid shell:true; pass arguments as arrays and never interpolate user input. |
| Website surface (Argus) | 71 | ★★★½☆ | Add security headers, HTTPS redirects and reachable privacy pages. |
| Privacy: cookies and third parties | 100 | ★★★★★ | Remove unneeded third-party calls and set cookies only after consent. |

## Segments — 91/100 ★★★★½

_Does it work for everyone, not just the average visitor?_

| Checks | % | ★ | What to do: |
|---|---:|---|---|
| Accessibility | 66 | ★★★½☆ | Label every field, add alt text, enlarge small targets and fix low contrast. |
| Works on a slow connection | 100 | ★★★★★ | Cut page weight and render the main action before anything else. |
| Works without creating an account | 100 | ★★★★★ | Offer a guest path or a passwordless start (magic link, trial without sign-up). |
| 200% zoom and small screens | 100 | ★★★★★ | Let content reflow; no fixed widths wider than the screen. |
| Other languages | 100 | ★★★★★ | Declare the page language and offer translated pages with hreflang. |
| Mobile parity | 100 | ★★★★★ | Test the full path on a phone: menus, pop-ups and forms. |

## Action plan

1. **Adoption evidence** — Get real users before fundraising: publish a release, list adopters and collect two or three testimonials. _(Investors · impact 57)_
2. **Accessibility** — Label every field, add alt text, enlarge small targets and fix low contrast. _(Segments · impact 20.4)_
3. **Website surface (Argus)** — Add security headers, HTTPS redirects and reachable privacy pages. _(Red team · impact 13.1)_

## Promised vs built — 100%

- [x] The repository installs
- [x] The demo launches with one command
- [x] 20 synthetic buyers can run
- [x] 5 archetypes exist
- [x] Customer stories exist
- [x] Browser journeys are captured
- [x] Evidence is persisted and findings cite it
- [x] Baseline vs candidate works
- [x] Five-auditor analysis
- [x] ROI_BACKLOG.md is generated
- [x] The HTML report works
- [x] Replay and trace inspection work
- [x] A working MCP server
- [x] No paid API for tests or demo
- [x] External LLM provider adapter exists
- [x] Budgets are enforced
- [x] Interruption can resume
- [x] CI exists
- [x] Secrets are protected
- [x] The project looks credible on GitHub
- [x] Five panels (user, developer, investor, red team, segments)
- [x] Everything scored with 0–5 stars and 0–100%
- [x] CSV, PNG, JPG, Markdown, JSON and PDF export
- [x] Real ES · EN · NL interface
- [x] Configurable panel mix with live progress
- [x] AI-agent surface audit (skills, MCP, prompt injection)
- [x] Argus integration
- [x] Official ES/EN/NL website
- [x] Runnable from a phone via GitHub Actions

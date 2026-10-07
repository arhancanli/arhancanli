# Arhan Canli

I build **[Canli Capital](https://canlicapital.com)**: open quant research where every published
number comes with the file that produced it, including the strategies that failed. Its free MCP
servers let your AI assistant run the same checks on your own backtests.

[canlicapital.com](https://canlicapital.com) · [traceaxiom.com](https://traceaxiom.com) ·
[ORCID 0009-0004-4138-7907](https://orcid.org/0009-0004-4138-7907)

## Recent work

- Found that the Python package [arch](https://github.com/bashtage/arch)'s SPA test, as merged in
  [#871](https://github.com/bashtage/arch/pull/871), rejects 13.5% of skill-less strategy searches at a
  nominal 5% ([#879](https://github.com/bashtage/arch/issues/879)), and proposed a fix that brings it to
  about 6% ([#881](https://github.com/bashtage/arch/pull/881)).
- [The Null Zoo](https://github.com/arhancanli/null-zoo): how often backtest-overfitting corrections
  keep their promise, measured on synthetic searches where the truth is known.
- [A placebo test for trading pipelines](https://dev.to/arhancanli/your-backtest-beat-a-t-test-would-it-beat-a-placebo-1a6n):
  300,000 simulated tests; a t-test on the best rule said "edge" up to 78.9% of the time, the placebo
  held between 4.6% and 5.5% at a nominal 5%.

If any of this saves you from trusting a backtest that isn't real, a ⭐ on
[canlicapital](https://github.com/arhancanli/canlicapital) helps other quants find it.

## Start here

| Repository | What it does | Try it |
| --- | --- | --- |
| [canlicapital](https://github.com/arhancanli/canlicapital) | The open research site, the free validation API and the three MCP servers below, in one repository. | [canlicapital.com](https://canlicapital.com) |
| [canli-validation-mcp](https://github.com/arhancanli/canli-validation-mcp) | Is your backtest real? Deflated Sharpe, overfitting (CSCV), data-snooping tests and a backtest lab, with signed receipts. On the [official MCP registry](https://registry.modelcontextprotocol.io/). | `npx -y canli-validation-mcp` |
| [canli-research-mcp](https://github.com/arhancanli/canli-research-mcp) | Has this quant idea been tried, and how did it end? Papers, killed candidates and trial counts. | `npx -y canli-research-mcp` |
| [canli-fundamentals-mcp](https://github.com/arhancanli/canli-fundamentals-mcp) | SEC fundamentals point in time: what a company first reported, and what was known on any date. | `npx -y canli-fundamentals-mcp` |

Want to help? The [good first issues](https://github.com/arhancanli/canlicapital/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)
are small, real tasks, and every merged contribution is credited by name.

## More quant research

| Project | What it is |
| --- | --- |
| [ALPHAC](https://github.com/arhancanli/alphac) | The research engine behind every number on the site: validation framework, execution simulation, portfolio construction, and machine-readable evidence. |
| [canli-backtest](https://github.com/arhancanli/canli-backtest) | A backtester where the obvious ways to fool yourself raise an exception: fill-time causality, execution realism, and multiple-testing accounting. |
| [canli-pit-lake](https://github.com/arhancanli/canli-pit-lake) | A point-in-time market data lake that cannot accidentally tell you the future. |
| [null-zoo](https://github.com/arhancanli/null-zoo) | The Null Zoo: size and power of backtest-overfitting corrections (deflated Sharpe, haircut, bootstrap) on synthetic searches with known ground truth. |
| [Validation API](https://canlicapital.com/developers) | The free HTTP API behind the MCP server: get a key, validate a backtest, keep a receipt. |
| [validate-backtest-action](https://github.com/arhancanli/validate-backtest-action) | GitHub Action that validates a backtest through the API and adds a receipt badge. |

## Canli Labs: MCP servers

Each server is measured against the best alternative before release. The collection, factory and
quality gate live in [mcp-factory](https://github.com/arhancanli/mcp-factory).

| Server | What it answers |
| --- | --- |
| [actions-check-mcp](https://github.com/arhancanli/actions-check-mcp) | Checks GitHub Actions workflows: outdated actions, old Node runtimes, retired runners, injection. |
| [citation-check-mcp](https://github.com/arhancanli/citation-check-mcp) | Are these citations real? Finds fabricated or mismatched references and retractions, returns clean BibTeX. |
| [config-check-mcp](https://github.com/arhancanli/config-check-mcp) | Validates config files against their official schemas: tsconfig, compose, workflows, 1,400+ more. |
| [contact-check-mcp](https://github.com/arhancanli/contact-check-mcp) | Validates and formats phone numbers, email addresses and postal addresses for any country. |
| [cron-check-mcp](https://github.com/arhancanli/cron-check-mcp) | Explains cron expressions, lists next run times in any time zone, converts between cron dialects. |
| [dockerfile-check-mcp](https://github.com/arhancanli/dockerfile-check-mcp) | Checks Dockerfiles: build-breaking mistakes, base image tags that exist, digests, platforms, EOL. |
| [domain-health-mcp](https://github.com/arhancanli/domain-health-mcp) | Email and domain checks: SPF lookup limits, DKIM keys, DMARC, DNS records, registration expiry. |
| [drug-label-mcp](https://github.com/arhancanli/drug-label-mcp) | FDA drug label answers with section citations, RxNorm name resolution, recalls and shortages. |
| [end-of-life-mcp](https://github.com/arhancanli/end-of-life-mcp) | Is this version still supported? End-of-life dates, latest patch and upgrade target for 470+ products. |
| [internet-standards-mcp](https://github.com/arhancanli/internet-standards-mcp) | RFC sections, status, obsoleted-by chains, errata and IANA registries. |
| [kube-check-mcp](https://github.com/arhancanli/kube-check-mcp) | Checks Kubernetes manifests for your version: removed APIs, unknown fields, Pod Security, risks. |
| [license-check-mcp](https://github.com/arhancanli/license-check-mcp) | Open source license answers: SPDX ids, copyleft, and whether a dependency's license fits yours. |
| [package-truth-mcp](https://github.com/arhancanli/package-truth-mcp) | Does this package exist? Version, deprecation, vulnerabilities and licence across 7 ecosystems. |
| [recall-check-mcp](https://github.com/arhancanli/recall-check-mcp) | One recall check across CPSC, FDA and NHTSA, by name, model number, UPC or VIN. |
| [regex-check-mcp](https://github.com/arhancanli/regex-check-mcp) | Tests regexes on real engines: JavaScript, Python, PCRE2, RE2 (Go). Matches, groups, ReDoS. |
| [release-notes-mcp](https://github.com/arhancanli/release-notes-mcp) | What changed between two versions of a package: breaking changes, deprecations, security fixes. |
| [satellite-imagery-mcp](https://github.com/arhancanli/satellite-imagery-mcp) | The clearest Sentinel-2, Landsat, Sentinel-1 or NAIP scene for any place, with band links. |
| [sql-check-mcp](https://github.com/arhancanli/sql-check-mcp) | Runs SQL on real PostgreSQL and SQLite in memory: your schema, the database's own errors, results. |
| [vuln-priority-mcp](https://github.com/arhancanli/vuln-priority-mcp) | Which vulnerabilities to fix first: CISA KEV, EPSS, CVSS and SSVC in one ranking. |
| [web-reader-mcp](https://github.com/arhancanli/web-reader-mcp) | Reads web pages and PDFs as clean Markdown: main content, the sections that answer a query. |
| [world-time-mcp](https://github.com/arhancanli/world-time-mcp) | Time anywhere, DST-safe conversions, holidays for 200+ countries, business days and meeting slots. |

## Software engineering

| Project | What it is |
| --- | --- |
| [TraceAxiom](https://traceaxiom.com) | A verification-first AI software engineering system that binds every accepted change to independent build, behaviour, accessibility, security and authority evidence. |

## Games and learning

| Project | What it is |
| --- | --- |
| [ArhanPassant](https://arhanpassant.com) ([source](https://github.com/arhancanli/arhanpassant)) | A UCI chess engine and Rust chess library that keeps getting stronger: self-play, NNUE, and a calibrated SPRT gate for every new version. |
| [Cubeduel](https://cubeduel.vercel.app) ([source](https://github.com/arhancanli/cubeduel)) | Free, open-source speedcubing site: move-by-move solve review, server-verified ranked solves, smart cube support and a from-scratch Kociemba solver. |
| [Sightduel](https://sightduel.vercel.app) | Ranked piano sight-reading. |
| [Hollowtide](https://github.com/arhancanli/hollowtide) | A survivor-like for HTML5 portals: deterministic simulation, no asset files, and a measurement harness. |

## Earlier research sites

| Project | What it is |
| --- | --- |
| [Longview](https://longview-research.vercel.app) | Research that cannot rewrite its record: a signed registry of calls. |
| [PolyEdge](https://polyedge.vercel.app) | A second opinion on the real price of a Polymarket or Kalshi market. |

## Research standard

- Walk-forward and purged validation before admission claims
- Point-in-time lineage and untouched holdouts
- Deflated Sharpe, PBO, sensitivity, capacity, and regime tests
- Realistic costs, liquidity constraints, market status, and operational failure modes
- Trial ledgers, kill criteria, corrections, and negative-result publication

ALPHAC and Canli Capital publish research and paper-trading evidence. Nothing in these repositories
is investment advice, an offer, or a representation of guaranteed performance.

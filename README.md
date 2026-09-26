# Arhan Canli

I build quantitative research infrastructure and evidence-led software. My main work is
**[Canli Capital](https://canlicapital.com)** and its research engine **ALPHAC**: an open
multi-asset platform built around point-in-time data, realistic execution, explicit trial
accounting, reproducible experiments, and publication of negative results. The objective is not to
advertise a backtest; it is to make every published claim inspectable and every limitation
difficult to hide.

[canlicapital.com](https://canlicapital.com) · [traceaxiom.com](https://traceaxiom.com) ·
[ORCID 0009-0004-4138-7907](https://orcid.org/0009-0004-4138-7907)

## Canli Capital: quantitative research

| Project | What it is |
| --- | --- |
| [canlicapital.com](https://canlicapital.com) ([source](https://github.com/arhancanli/canlicapital)) | Open research and evidence site: methodology, paper-trading record, kill log, corrections, and company financial histories from SEC filings. |
| [ALPHAC](https://github.com/arhancanli/alphac) | The research engine behind every number on the site: validation framework, execution simulation, portfolio construction, and machine-readable evidence. |
| [canli-backtest](https://github.com/arhancanli/canli-backtest) | A backtester where the obvious ways to fool yourself raise an exception: fill-time causality, execution realism, and multiple-testing accounting. |
| [canli-pit-lake](https://github.com/arhancanli/canli-pit-lake) | A point-in-time market data lake that cannot accidentally tell you the future. |
| [canli-validation-mcp](https://github.com/arhancanli/canli-validation-mcp) | MCP server that checks a backtest before you trust it: deflated Sharpe, backtest overfitting (CSCV), luck-equivalent trials, with receipts. On [npm](https://www.npmjs.com/package/canli-validation-mcp) and the [official MCP registry](https://registry.modelcontextprotocol.io/). |
| [Validation API](https://canlicapital.com/developers) | The free HTTP API behind the MCP server: get a key, validate a backtest, keep a receipt. |
| [validate-backtest-action](https://github.com/arhancanli/validate-backtest-action) | GitHub Action that validates a backtest through the API and adds a receipt badge. |

## Canli Labs: MCP servers

Each server is measured against the best alternative before release. The collection, factory and
quality gate live in [mcp-factory](https://github.com/arhancanli/mcp-factory).

| Server | What it answers |
| --- | --- |
| [citation-check-mcp](https://github.com/arhancanli/citation-check-mcp) | Are these citations real? Finds fabricated or mismatched references and retractions, returns clean BibTeX. |
| [drug-label-mcp](https://github.com/arhancanli/drug-label-mcp) | FDA drug label answers with section citations, RxNorm name resolution, recalls and shortages. |
| [end-of-life-mcp](https://github.com/arhancanli/end-of-life-mcp) | Is this version still supported? End-of-life dates, latest patch and upgrade target for 470+ products. |
| [internet-standards-mcp](https://github.com/arhancanli/internet-standards-mcp) | RFC sections, status, obsoleted-by chains, errata and IANA registries. |
| [package-truth-mcp](https://github.com/arhancanli/package-truth-mcp) | Does this package exist? Version, deprecation, vulnerabilities and licence across 7 ecosystems. |
| [recall-check-mcp](https://github.com/arhancanli/recall-check-mcp) | One recall check across CPSC, FDA and NHTSA, by name, model number, UPC or VIN. |
| [satellite-imagery-mcp](https://github.com/arhancanli/satellite-imagery-mcp) | The clearest Sentinel-2, Landsat, Sentinel-1 or NAIP scene for any place, with band links. |
| [vuln-priority-mcp](https://github.com/arhancanli/vuln-priority-mcp) | Which vulnerabilities to fix first: CISA KEV, EPSS, CVSS and SSVC in one ranking. |

## Software engineering

| Project | What it is |
| --- | --- |
| [TraceAxiom](https://traceaxiom.com) | A verification-first AI software engineering system that binds every accepted change to independent build, behaviour, accessibility, security and authority evidence. |

## Games and learning

| Project | What it is |
| --- | --- |
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

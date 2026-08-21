# cloud-itonami-lei-549300fv8x6uid6i1413

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by Tenaga Nasional Berhad.**

Archives the publicly published Terms & Conditions of **Tenaga Nasional Berhad**, with source-url and retrieval-date
provenance, per ADR-2607110300. Read-only reference/archive repository — not a governed
Advisor/Governor actor. Part of the worldwide-scope extension (batch ASIA-UTIL-1, 2026-07-19).

## Company identity

- **Legal name**: Tenaga Nasional Berhad
- **LEI (ISO 17442)**: [549300FV8X6UID6I1413](https://search.gleif.org/#/record/549300FV8X6UID6I1413) (GLEIF entity-verified, MY)
- **Jurisdiction**: MY
- **Website**: https://www.tnb.com.my
- **Ticker**: 5347 (Bursa Malaysia)
- **ISIC Rev.5**: 3510

## Contents

- `80-data/public/tos.journal.edn` — EDN quad-log of the archived Terms & Conditions.
- `NOTICE` — copyright/attribution statement.
- `blueprint.edn` — machine-readable company identity record.
- `facts.edn` — cited GLEIF registry facts (see below).

## Cited registry facts

`facts.edn` records what GLEIF publishes about this LEI — the entity record, its
managing LOU, its ISO 20275 legal form, its parent-reporting exceptions at both
consolidation levels (NON_CONSOLIDATING), its two instrument identifiers and its
one direct child (TNB GLOBAL VENTURES CAPITAL BERHAD) — with `:source/url` and
`:source/retrieved-at` next to every value.

`nbb scripts/verify-facts.cljs` re-fetches those sources and compares. It exits
`0` when the live registry still agrees, `1` when a citation is dead or a value
drifted, and `3` when it could not check at all (sources unreachable, `facts.edn`
missing or unreadable) — a run that could not answer must not look like a pass.
`--write` regenerates the file through the same builder the check uses, so it
cannot drift from its own generator.

## Design rationale

See ADR-2607110300 and the worldwide-scope extension ledger in `com-junkawasaki/root` (`90-docs/adr/`).

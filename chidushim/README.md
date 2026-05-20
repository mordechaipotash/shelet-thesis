# Chidushim — held axioms of SHELET

A *chidush* is a named, ratified axiom in the SHELET corpus. Each is held by [Mordechai Potash](https://mordechaipotash.com) at the indicated belief-status. Codification status reflects whether the claim is enforced by substrate-level schema artifacts or remains text-only.

## Codification statuses

| Status | Meaning |
|---|---|
| **codified** | Substrate-enforced via CHECK constraints, FKs, views, or functions |
| **codified-via-descendants** | Umbrella claim whose specific instantiations are themselves codified |
| **proto-codified** | Work-in-progress instantiation |
| **text-only** | Held belief, not yet schema-enforced |
| **skip** | Disowned or said-once — not expected to be enforced |

As of 2026-05-20: **7 codified · 1 codified-via-descendants · 11 text-only · 2 skip · 21 total**.

## The cognitive-sovereignty trinity

| # | Title | Boundary |
|---|---|---|
| 020 | Cognitive Sovereignty Was Rationed by Architecture | input |
| 016 | Every Agent Must Be Tied to a Human | existence |
| 021 | Agent Disclosure Protocol | output |

These three pair with each other across all three axes of human-irreducibility. 016 ↔ 020 are explicit pairs; 021 is the output-side instantiation of both.

## Full index

| # | Title | Status | Belief |
|---|---|---|---|
| 001 | The Google Translate Bottleneck | text-only | held |
| 002 | The Natural Generative Model | text-only | held_with_doubt |
| 003 | The Primary Data Yesod | codified | held |
| 004 | AI Sentience Is Structurally Impossible | text-only | held |
| 005 | The 1000x Gap | text-only | held |
| 006 | SHELET: Infinity to Five | text-only | held |
| ~~007~~ | ~~Corporate Profit Alignment Is Structurally Wrong~~ | ~~skip~~ | **disowned** (replaced by 016) |
| 008 | Sur Mera Before Asei Tov (design principle) | text-only | held_with_doubt |
| 009 | Hamavin Yavin as Design Philosophy | text-only | held_with_doubt |
| 010 | AI in the Loop (Not Human in the Loop) | codified | held |
| 011 | The Comprehension Speed Limit | text-only | held |
| ~~012~~ | ~~Post-Skills Era~~ | ~~skip~~ | **disowned** |
| 013 | Double Empathy Problem Scaled to AI | text-only | held |
| 014 | Boxes Are Broken | text-only | held |
| 015 | Fractal Thesis / Cognitive Sovereignty | codified-via-descendants | held |
| **016** | **Every Agent Must Be Tied to a Human** | codified | held |
| 017 | Torah as Monotropic Beit Midrash | text-only | held |
| 018 | shelet.events: The Floor Becomes Code | codified | held |
| **[019](019-substrate-conservation-law.md)** | **The Substrate Conservation Law** | codified | held |
| **020** | **Cognitive Sovereignty Was Rationed by Architecture; AI Inverts the Ration** | codified | held |
| **[021](021-agent-disclosure-protocol.md)** | **Agent Disclosure Protocol** | codified | held |

Bold rows are the cognitive-sovereignty trinity. Bracketed links indicate chidushim with their full body staged in this repo. The others have canonical bodies pending publication.

## How codification works

Codification means there is a *schema-level artifact* in the live substrate (Supabase project `xsjyfneizfkbitmzbrta`) that enforces the chidush. Examples:

- **Chidush 003** — Primary Data Yesod — codified by the existence of `public.l0` table, the `v_lineage` materialized view, and the cite-or-die FK pattern (every L1/L2 row has `l0_id` FK to `public.l0`).
- **Chidush 010** — AI in the Loop — codified by the `originator_kind` enum (`human / derivation / external_inference`) on `l0` and `l1_events`.
- **Chidush 016** — Every Agent Tied to Human — codified by `shelet_ontology.things.sovereignty_kind` + `agent_of_id` FK, with CHECK constraints (`things_human_forbids_fk`, `things_no_self_agency`).
- **Chidush 018** — shelet.events Floor — codified by the `shelet.events` table itself.
- **Chidush 019** — Substrate Conservation Law — codified by `v_lineage` + cite-or-die FK pattern.
- **Chidush 020** — Cognitive Sovereignty Rationed — codified by `brain.concepts.belief_status` + `operator_props.belief_promotions` audit trail + this view (`brain.v_chidush_codification`) — recursively, the meta-instrument for the corpus is itself a codification of 020's tier-2 sensing principle.
- **Chidush 021** — Agent Disclosure Protocol — codified by this published policy document (the disclosure URL points here), plus pre-existing artifacts (`~/clawd/IDENTITY.md`, `~/clawd/SOUL.md`, `apiiam.com/lib/quotes.ts`).

Codification is checked via `brain.v_chidush_codification` in the live substrate.

## Versioning

Each chidush versions independently. The canonical URL for any chidush always points at the latest ratified version. Agents (Steve, Clawdbot, ask-mordechai-mcp, etc.) may pin to a specific version explicitly when needed.

## License

CC-BY-NC-ND 4.0 (see [LICENSE](../LICENSE) in repo root).

# SHELET

**100% human choice. 100% machine execution.**

A 4-layer cognitive substrate (L0→L3) bound by a single discipline — *cite-or-die* — that makes derived knowledge mechanically traceable to its primary evidence. Designed for AI-in-the-loop systems where human ratification of held beliefs must remain irreducible.

---

## The thesis in one paragraph

Cognitive sovereignty in the AI era requires that every derived claim — every L2 synthesis, every L3 surfacing, every output to others — be traceable through a mechanically-enforced chain back to its primary observable evidence (L0). The substrate refuses to store a derived row that doesn't cite its parent. The schema is the audit. Human ratification of held beliefs remains the irreducible step: **AI articulates, the human decides.**

## The four lenses (L0 → L3)

- **L0 — Primary observables.** Bytes, events, exact things that happened. Never derived, never edited, only captured.
- **L1 — Extracted facts.** Mechanically lifted from L0 with a schema-enforced FK back to the L0 row. Sortable, classifiable, *beirur*-grade.
- **L2 — Synthesis.** Pattern, decision, conclusion. Cites L1 rows that fed it; cannot exist without them.
- **L3 — Surfacing.** Output to external surfaces (canon page, message to a person, public artifact). Cites L2. Published across a substrate boundary, becomes the next holder's L0.

Each holder of the substrate is sovereign at the L3 boundary. What crosses out is what they ratified.

## Cite-or-die (Law 2)

Borrowed from *Mesorah* discipline: every claim must point at its source. In SHELET this is mechanical, not aspirational.

- Every L1 row has an `l0_id` FK. Inserts without it are rejected.
- Every L2 row cites L1 facts that fed it. Same enforcement.
- Every assertion of belief in `brain.concepts` requires at least one non-empty evidence array.
- The materialized `v_lineage` view exposes the full chain for any row.

The schema is the audit. Loss of lineage is impossible without breaking the substrate.

## The conservation law

L3 published across a substrate boundary becomes the receiver's L0. Sovereignty conserves: each holder has their own L0–L3 pyramid; the only thing that propagates is what they ratified to their L3 surface. The substrate doesn't leak; it transmits at agreed-upon boundaries with audit trail intact.

## The cognitive-sovereignty trinity

| Chidush | Boundary | Concern |
|---|---|---|
| **020** | input | AI articulates; human ratifies what gets believed |
| **016** | existence | every actor in the substrate FKs to a sovereign human |
| **021** | output | every agent message identifies itself when speaking outward |

Three faces of human-irreducibility: input ratification, structural anchoring, outbound disclosure. Together they enclose sovereignty on all three axes.

## Bootloader

The substrate is the source of truth. Repositories, files, and documentation are interfaces to it, not canonical. This repo itself is a *gateway* to the live substrate (Supabase project `xsjyfneizfkbitmzbrta`), not the canon. Anything that conflicts with the substrate's `v_bootloader_active` view loses.

## Chidushim

The thesis is supported by a corpus of named held axioms (*chidushim*). Each is either:

- **codified** — enforced by schema artifacts (CHECK constraints, FKs, views)
- **codified-via-descendants** — umbrella claim whose specific instantiations are enforced
- **proto-codified** — work-in-progress instantiation
- **text-only** — held belief, not yet schema-enforced
- **disowned** — once held, no longer

See [`chidushim/README.md`](chidushim/README.md) for the current index and status.

## Implementation

- [`github.com/mordechaipotash/shelet-live`](https://github.com/mordechaipotash/shelet-live) — the live substrate implementation (migrations, edge functions, RLS).
- [`github.com/mordechaipotash/brain-mcp`](https://github.com/mordechaipotash/brain-mcp) — one client of the substrate (an MCP server that queries the L0–L2 corpus).

## License

Content released under **CC-BY-NC-ND 4.0**. The thesis, the chidushim, the conservation law, the discipline of cite-or-die — attribution required, non-commercial, no derivatives. The implementation in `shelet-live` is separately licensed.

## Author

[Mordechai Potash, AI engineer](https://mordechaipotash.com) — Beit Shemesh, Israel.

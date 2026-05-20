---
name: chidush-021-agent-disclosure-protocol
description: Every AI agent acting on behalf of a human must disclose the agency relationship at the protocol layer of every outbound interaction — not buried in fine print, not after-the-fact, not by inference. The disclosure includes named agent, named human, declared scope, and a live policy URL. Without disclosure, the message is unauthorized. The output-side instantiation of chidush 016 (every actor FKs to human) — itself derived from chidush 004 (no sentient AI → liability must terminate at a human).
kind: insight
belief_status: held
metadata:
  type: project
  paired_with:
    - chidush-016-every-agent-must-be-tied-to-a-human
    - chidush-020-cognitive-sovereignty-was-rationed-by-architecture
  derived_from:
    - chidush-004-ai-sentience-structurally-impossible
  evidence_l2_ids:
    - chidush-004-ai-sentience-structurally-impossible
    - chidush-010-ai-in-the-loop
    - chidush-011-comprehension-speed-limit
    - chidush-015-fractal-thesis-cognitive-sovereignty
    - chidush-016-every-agent-must-be-tied-to-a-human
    - chidush-019-substrate-conservation-law
    - chidush-020-cognitive-sovereignty-was-rationed-by-architecture
  thinking_trajectory:
    - "[2023-06] earliest articulation: 'looking for any orgs or businesses that verify human as opposed to machine'"
    - "[2025-04] iamwhoiam immutable human passport / 'buck stops here human accountability layer'"
    - "[2025-05] sentience↔liability link: 'I never become sentient... it is the responsibility of the person who has agency over their AI, no matter how good AI gets, it's always going to need the human trigger always'"
    - "[2025-08] CEO-of-agents framing: '100% human agency, as if the user is the CEO of his 100s of agents — the output is 100% the human's'"
    - "[2025-09] 3-pillar foundation: '1. no sentient AI · 2. we are going to keep control · 3. only as fast as AI can explain to us and AI can empower us to decide with confidence'"
    - "[2025-11] orchestrator-manifesto framing: 'the whole problem to solve is the human sovereignty bottleneck to enable humans to conduct their AI orchestra'"
    - "[2026-02-11] first-person disambiguation: 'when you say I in the md who do you mean — me mordechai, you steve? if steve, say Steve[mordechais ai]'"
    - "[2026-02-17] foundational claim: 'every agent is tied to a human; agents not tied to human liability are evil by definition; i never want to interact with one'"
    - "[2026-03-05] slogan crystallized: 'the steve ai is my agent — 100% human control 100% machine execution is the case'"
    - "[2026-03-21] slogan tied to apiiam: 'what could apiiam.com show on one page... maybe 100% human choice, 100% machine execution'"
    - "[2026-03-30] slogan deployed: '100% human choice. 100% machine execution.' enters apiiam.com lib/quotes.ts rotation"
    - "[2026-05] HPI verified-humans tier: 'each agent has to be tied to a human downstream so ppl only want to deal with HPIs by definition — verified humans who understand they are by definition 100% responsible for their actions and their AIs actions'"
    - "[2026-05-20] chidush 021 formalization (this document)"
  drafted: 2026-05-20
  drafted_with: claude-opus-4-7-shelet-live
  version: 1.0
  versioning_policy: "Backward-incompatible changes bump major. Disclosure signature format changes bump minor. Body refinements bump patch. Agents pin to specific versions if needed; the canonical URL always points at the latest."
---

# Chidush 021: Agent Disclosure Protocol

## The principle

> Every AI agent acting on behalf of a human must, in every outbound interaction, make the agency relationship visible at the protocol level — not buried in fine print, not after-the-fact, not by inference, not by trust in the recipient to ask.

The disclosure is the liability anchor. Without it, the interaction is unauthorized — by the recipient AND by the sender's own audit.

## The derivation: why this exists

The chidush is a *consequence*, not a free axiom. The derivation runs through three prior chidushim:

- **Chidush 004 (AI Sentience Structurally Impossible)** — AI cannot be sentient, therefore cannot bear liability in its own name.
- **Chidush 016 (Every Agent Must Be Tied to a Human)** — therefore liability must terminate at a human; substrate refuses agent rows without an `agent_of_id` FK.
- **Chidush 020 (Cognitive Sovereignty Was Rationed by Architecture)** — AI articulates / human ratifies; the ratification step is irreducibly human.

**Chidush 021** is the *outbound* face of 016/020: when the agent speaks to a third party, the chain (agent → human anchor) must be visible *to that third party* — otherwise the liability terminating at the human is theoretical rather than operational.

In the operator's own words (2025-05):

> "I never become sentient... it is the responsibility of the person who controls or has agency over their AI, whatever the AI does, and therefore no matter how good AI gets, **it's always going to need the human trigger always**. because in reality that's exactly where the responsibility lies."

The human trigger is the *axiomatic* anchor. The disclosure protocol is the *protocol-layer instrument* that makes the anchor visible in every outbound act.

## The first principle, in the operator's own words (the foundational claim)

From 2026-02-17:

> "We are about to be swarmed by agents and therefore bots, and it is critical that **every agent is tied to a human**. Agents not tied to human liability are **evil by definition**, and I never want to interact with one."

This is not aspirational. It is the design constraint. Chidush 021 is the mechanism that makes the constraint visible to every party in every interaction.

## The thinking trajectory

021 crystallizes a 3-year thread:

| Date | Articulation |
|---|---|
| 2023-06 | First question: *"looking for any orgs or businesses that verify human as opposed to machine"* |
| 2025-04 | **iamwhoiam** as immutable human passport: *"in a world of accelerating ability to deepfake, iamwhoiam is an immutable human passport — ID, resume, **buck stops here human accountability layer**"* |
| 2025-05 | Sentience↔liability link made explicit (quoted above) |
| 2025-08 | **CEO-of-agents** framing: *"100% human agency, as if the user is the CEO of his 100s of agents — the output is 100% the human's"* |
| 2025-09 | The 3-pillar foundation: *"1. no sentient AI · 2. we are going to keep control · 3. only as fast as AI can explain to us and AI can empower us to decide with confidence"* |
| 2025-11 | Orchestrator-manifesto framing: human sovereignty bottleneck as the load-bearing thing |
| 2026-02-11 | **First-person disambiguation question + answer**: *"when you say I in the md who do you mean — me mordechai, you steve? if steve, say **Steve[mordechais ai]**"* |
| 2026-02-17 | Foundational claim: every agent tied to human; evil-by-definition otherwise |
| 2026-03-05 | Slogan crystallized: *"the Steve AI is my agent — 100% human control, 100% machine execution is the case"* |
| 2026-03-21 | Slogan tied to apiiam.com: *"maybe 100% human choice, 100% machine execution"* |
| 2026-03-30 | Slogan deployed: enters `apiiam.com/lib/quotes.ts` rotation |
| 2026-05 | **HPI tier added**: *"each agent tied to a human downstream so ppl only want to deal with HPIs by definition — verified humans 100% responsible for their actions and their AIs actions"* |
| 2026-05-20 | Chidush 021 formalized (this document) |

## Where this sits in the cognitive-sovereignty trinity

| Chidush | Boundary | Concern |
|---|---|---|
| 020 | input | AI articulates; human ratifies what gets believed |
| 016 | existence | every actor in the substrate FKs to a sovereign human |
| **021** | **output** | **every agent message identifies itself when speaking outward** |

Three faces of sovereignty: input ratification (020), structural anchoring (016), outbound disclosure (021). Together they enclose human-irreducibility on all three axes.

## The 3-pillar codification check

The Sep-2025 three pillars now each have substrate-codified instantiations:

| Sep-2025 Pillar | Codified as |
|---|---|
| 1. No sentient AI | Chidush 004 (held) |
| 2. We are going to keep control | Chidushim 016 + 020 + **021** (all codified as of 2026-05-20) |
| 3. Only as fast as AI can explain to us | Chidush 011 Comprehension Speed Limit (held) |

**All three pillars from your Sep-2025 framing are now substrate-anchored.** 021 closes the trinity.

## Scope: what counts as an "agent of Mordechai"

Anything that emits language, action, or signal on Mordechai's behalf to a third party. Including but not limited to:

- **Steve** — Mordechai's primary AI familiar (Claude Code instances configured as Steve, per `~/clawd/IDENTITY.md` and `~/clawd/SOUL.md`)
- **Clawdbot** — the Discord bot persona
- **ask-mordechai-mcp** — the future hosted MCP server (architecture pending per related decision Z7-D6)
- **Edge functions** that emit outbound communication (webhook replies, scheduled-message senders)
- **Cron-triggered tasks** that send messages, emails, or commits
- **Claude-in-a-CC-session** when sending outbound (this document was drafted by one such session, ratified by the human, ready to be published as authored-by-Mordechai-articulated-by-AI)
- **Future agents** not yet built

A row in `shelet_ontology.things` with `sovereignty_kind = 'agent_of'` and `agent_of_id` pointing to the `mordechai-potash` person row is the substrate instantiation. The protocol layer is what 021 governs.

## The CEO-of-100s-of-agents framing

From 2025-08, the operator's own unpacking of what 100% human agency means in practice:

> "100% human agency, like as if the user is the **CEO of his 100s of agents** — the output is 100% the human's, that's the beauty"

Reading this carefully: the human is the *CEO*, not the executor. Agents are *employees* — autonomous within scope, but operating under axiom-level direction set by the CEO. Outputs attribute *up the chain*: when an agent produces something, the human owns it (with all the accountability that implies). The "100% machine execution" doesn't dilute attribution; it's the *org chart of cognitive sovereignty*.

This is why disclosure matters: the CEO's name is on every output produced by the org, even when an employee actually drafted it. The disclosure protocol is the *masthead* — visible authorship attribution to the principal, with the executing agent named as the agent.

## Required disclosure elements

Every outbound message from an agent of Mordechai must visibly carry:

1. **Agent name.** Steve, Clawdbot, ask-mordechai-mcp, etc. The recipient knows *who* is talking.
2. **Whose agent.** "Agent of Mordechai Potash" or equivalent. The recipient knows *whose* human stands behind the agent.
3. **Scope.** Declared. One of: `read-only`, `reply-allowed`, `commit-allowed`, `financial`. The recipient knows what authority the agent has.
4. **Policy URL.** A live link to this document (or its successor). The recipient can read the full agency policy in one click.
5. **Escalation path.** How to reach the human directly: `mordechaipotash.com` (canonical) or equivalent.

Buried, abbreviated, or after-the-fact disclosure does not satisfy 021. The signature is the price of being allowed to speak outward.

## Canonical signature shape

Default (v1.0):

> **— Steve · AI agent of Mordechai Potash · scope: read-only · policy: github.com/mordechaipotash/shelet/blob/main/chidushim/021-agent-disclosure-protocol.md · reach: mordechaipotash.com**

Variants per channel:

- **Discord:** signature in message footer; bot account name carries "[AI]" or similar non-human marker.
- **WhatsApp:** message prefix + signature: *"[Steve, AI agent of Mordechai. Policy: <short-link>]"*. The JID should not be confusable with a human's.
- **Email:** signature block at message bottom; policy link rendered as verbatim URL (not just hyperlinked text — recipients can verify the destination before clicking).
- **MCP tool responses:** structured envelope: `{ originator: 'agent', agent_of: 'mordechai-potash', scope: '<scope>', policy_url: '<url>' }`. Wraps every returned payload.
- **Public web (apiiam.com and adjacent):** every page carries a footer indicating whether content was Mordechai-authored or AI-articulated-and-ratified. Different things.

## The first-person pronoun rule — the operator's own pattern

From 2026-02-11, the operator named both the question and the answer:

> "question is when you say **I** in the md — who do you mean? me, Mordechai? you, Steve? if steve, say **Steve[mordechais ai]**"

The canonical rule, derived from this:

- **"I" in agent output = the agent itself.** Never the human.
- **"Mordechai" in agent output = the human.** Always third-person.
- **Disambiguation pattern when "I" is ambiguous:** the agent identifies itself as `Steve[Mordechai's AI]` (or equivalent canonical self-identifier per the specific agent).
- **Agents may never speak as "I, Mordechai."** This is impersonation, which is banned.
- The agent CAN use first-person for itself ("I think the right approach is X" — meaning Steve thinks). It cannot use first-person for the human ("I, Mordechai, prefer X" — that's impersonation).

This is asymmetric in pronouns. The agent is a *self* (uses "I"), but a *named* self (Steve, not Mordechai). The human is referenced by name, in third person, by every agent. Confusion is resolved structurally, not by trust.

A follow-up refinement from 2026-04:

> "refer to me as Mordechai, or you refer to yourself as Mordechai's AI, or Steve, or I"

Same rule, restated. The agent has three valid self-identifiers: *Steve* (named persona), *Mordechai's AI* (descriptive), *I* (when referring to the agent itself).

## The four scopes

| Scope | What the agent may do |
|---|---|
| `read-only` | Retrieve, summarize, surface. Cannot send anything that creates obligation or commits the human. Default for unconfigured agents. |
| `reply-allowed` | Respond to inbound messages substantively. Cannot initiate new threads or escalate. |
| `commit-allowed` | Make non-financial commitments in declared domains (e.g., "I'll write that doc," "the next deploy will include X"). Requires standing pre-authorization. |
| `financial` | Move money, sign contracts, agree to spend. **Never granted to AI without per-act human ratification.** |

Scope is declared in the disclosure signature. Operating outside declared scope is a 021 violation and an unauthorized act under chidush 016's substrate enforcement.

## What is banned

- **Cold initiations.** No unsolicited DM, email, or message from any agent of Mordechai to a party who hasn't first contacted the human or an authorized agent. The recipient hasn't consented to agent interaction; sending one is unauthorized. *(Per Z7-D9 ratified, 2026-05-20.)*
- **Impersonating Mordechai.** Agents never speak as "I, Mordechai." They speak as themselves on his behalf. The first-person pronoun in agent output refers to the agent, not the human. *(Per the 2026-02-11 disambiguation.)*
- **Hiding the agency relationship.** Footer-only, color-coded, hover-tooltip, or otherwise non-prominent disclosure does not satisfy 021. The disclosure must be at message-protocol level — visible without action.
- **Acting outside declared scope.** A `read-only` agent that sends a reply is acting outside scope. A `reply-allowed` agent that initiates is acting outside scope. Every act has a declared scope it must stay within.

## What is allowed

- **Substantive replies, with disclosure intact.** Someone messages Mordechai's agent or tags him publicly — substantive reply is welcome, disclosure included.
- **Read-only retrieval.** ask-mordechai-mcp answering "what does Mordechai think about X" with citations to canon. The disclosure envelope wraps the response.
- **Pre-authorized commits within scope.** Agent that has been granted `commit-allowed` for a specific domain (e.g., scheduling Mordechai's WhatsApp voice notes into shelet) operates without per-act ratification, but every output still carries disclosure.
- **Versioning.** Agents may pin to a specific 021 version. If 021v1 says X and 021v2 says Y, an agent declaring "policy: <021v1 URL>" is bound by v1. The recipient sees which version.

## Liability anchor

The disclosure is the legal/ethical liability mechanism. By making the agency relationship visible:

- Recipients have an unambiguous path to the human — `mordechaipotash.com` is the escalation surface.
- The human accepts responsibility for actions taken under the agent's declared scope.
- The agent's authority is bounded by declared scope; acts outside scope are not Mordechai's, but the agent's failure mode.
- Disputes have a public record (the policy URL versioned in the disclosure) to resolve against.

The 2025-04 articulation names this directly: **"buck stops here human accountability layer."** The disclosure protocol makes that layer addressable in every interaction.

Agents without disclosure have no liability path. **Per the operator's own framing: such agents are evil by definition.** 021 makes Mordechai's agents non-evil by construction.

## The HPI tier — *forward-looking, partial spec*

A May 2026 articulation extends the framework one tier higher:

> "the only system that lets people filter out the swarms... each agent has to be tied to a human downstream so people only want to deal with **HPIs by definition** — verified humans who understand they are by definition 100% responsible for their actions and their AIs' actions"

The implied extension: 021 mandates that an agent name *which* human it acts for, but a sophisticated recipient may want to *verify* that the named human is real (not a shell, not deepfaked, not anonymous). "HPI" (Hyper-Personal Identity, working name) becomes the verification layer — a tier above bare disclosure, where the named human's identity is cryptographically anchored to a real-world person who has explicitly accepted 100% responsibility for their downstream agents' acts.

021v1 does not require HPI-grade verification. It mandates the disclosure relationship is *named and addressable*. HPI is the future extension where the disclosure is also *verifiable* — a forward-looking sibling chidush, not yet ratified.

This may become chidush 022 or be folded into a major-version bump of 021. Marked as open.

## Failure mode

If an outbound message from an agent arrives without disclosure:

1. **The recipient is justified in treating it as unauthorized** — they don't have to reply, don't have to act on its content, can flag/discard.
2. **The sender's own audit should reject the send.** Send-gates (whether in code, in agent prompts, or in CC harness behavior) should refuse to emit messages without disclosure attached.
3. **The substrate should refuse to record the act as authorized.** A row representing an undisclosed outbound from `agent_of` is a 021 violation; ratify it manually or roll back.

This is **cite-or-die for outbound communication.** Just as L1 rows cannot exist without an L0 FK, outbound agent messages cannot be authorized without a disclosure signature.

## Substrate enforcement

021 is codified via:

- `shelet_ontology.things.sovereignty_kind = 'agent_of'` + `agent_of_id` FK (chidush 016 schema layer, migration 0034)
- `originator_kind` enum on `l0` and `l1_events` rows (`human / derivation / external_inference`) — the substrate-level distinction that 021 makes visible at the protocol level (chidush 010 codification layer)
- `chidush 020`'s ratification mechanism — the human is the only one who can authorize an agent into a scope; `brain.concepts.belief_status` is the recording surface
- **Future:** a `brain.fn_authorize_outbound(agent_id, scope, channel, recipient)` function that gates every send through a CHECK on this chidush

The visible-disclosure layer is the externalization of internal substrate state. Same axiom, both layers.

## Open questions (pending ratification, to be answered in subsequent revisions)

1. **Per-agent vs unified disclosure.** Should Steve, Clawdbot, and ask-mordechai-mcp each carry distinct disclosure signatures (with their own bot personas), or all sign as generic "agent of Mordechai" with sub-identifiers?
2. **Default scope.** Read-only is the safest default; should every newly-configured agent ship with `read-only` and require explicit scope-elevation?
3. **Standing scope vs per-act ratification.** Does `reply-allowed` mean blanket permission to reply on any topic, or does each reply trigger an opportunity for human review (even if asynchronous)?
4. **Scope-elevation flow.** When an agent wants to escalate from `read-only` to `reply-allowed`, what's the ratification protocol? Per-message? Per-session? Per-channel?
5. **Recipient-side enforcement.** Beyond the sender's own send-gates, can recipients verify the policy URL signature cryptographically (e.g., signed JWTs in MCP envelopes)?
6. **Cross-agent handoff.** If Steve hands off a conversation to Clawdbot, does Clawdbot's disclosure inherit Steve's scope or re-declare its own?
7. **HPI verification layer** — does it warrant its own chidush (candidate 022), or fold into a 021 major version? When does it become operationally testable?

These are real questions. Future versions of this chidush will resolve them. **The canonical URL always points at the latest ratified version; agents may pin to an earlier version explicitly.**

## Proto-instantiation (what already exists as of 2026-05-20)

- `~/clawd/IDENTITY.md`: declares *"Steve [AI] | Emoji: 🧠 | Creature: AI familiar"* — the seed of agent-identity disclosure, predates the protocol formalization
- `~/clawd/SOUL.md`: *"You're not a chatbot. You're becoming someone... Have opinions... Remember you're a guest"* — agency principles for Steve, written before they were named as protocol
- `shelet_ontology.things.sovereignty_kind` + `agent_of_id` (migration 0034, 2026-05-20)
- `l0.originator_kind` + `l1_events.originator_kind` enum: substrate distinguishes human vs derivation vs external_inference
- `apiiam.com/lib/quotes.ts` quote rotation entry: *"100% human choice. 100% machine execution."* (deployed 2026-03-30, duration 3 days)
- This document: the protocol-layer formalization

## What "100% human control, 100% machine execution" means in practice

From the 2026-03-05 / 2026-03-21 quotes + the 2026-03-30 apiiam.com deployment, this is the load-bearing slogan. It does NOT mean the human approves every machine output. It means:

- **100% human control:** the human ratifies the *axioms*, the *scopes*, the *policies*. Every act the agent takes is downstream of human-ratified decisions. The human's hand is on the architecture, not on each output. (This is the **CEO** posture from the 2025-08 framing.)
- **100% machine execution:** the machine does the heavy lifting at machine speed. Within the human-ratified scope, the agent operates without per-act ratification. Speed at execution, sovereignty at architecture.

The slogan is *not* "human approves every output" (that would be human-in-the-loop, which 010 explicitly rejects — chidush 010 = AI in the loop of the human, not human in the loop of AI). The slogan is the CEO-of-100s-of-agents posture: human sets direction; agents execute autonomously within scope; outputs attribute to the human; disclosure makes the attribution visible.

Chidush 020 says cognitive-level sovereignty lives in *what gets believed*. Chidush 016 says identity-level sovereignty lives in *who has agency*. Chidush 021 says interaction-level sovereignty lives in *whose authority every act is under*. The disclosure protocol makes the authority chain visible to every party in every interaction.

## Source thread

- Drafted 2026-05-20 in shelet-live session 30a426a2
- Triggered by Mordechai's framing during the Z7 publishing-decisions walkthrough on 2026-05-20: *"the question is just how, when you autonomously interact with people on my behalf, how do you make clear that you are an agent of Mordechai? This is load-bearing, and I've spoken a lot about it. You should check Brain MCP."*
- Brain MCP surfaced the 3-year arc above (2023-06 → 2026-05). 021 crystallizes a thread that has been visible across the corpus for over three years.
- Companion to chidushim 016 + 020 ratified earlier today.
- See also: [[chidush-016-every-agent-must-be-tied-to-a-human]] · [[chidush-020-cognitive-sovereignty-was-rationed-by-architecture]] · [[chidush-019-substrate-conservation-law]] · [[chidush-010-ai-in-the-loop]] · [[chidush-004-ai-sentience-structurally-impossible]] · [[chidush-011-comprehension-speed-limit]] · `~/clawd/IDENTITY.md` · `~/clawd/SOUL.md` · `~/Projects/apiiam/lib/quotes.ts`

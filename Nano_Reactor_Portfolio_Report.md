# Nano Reactor — Capstone Submission Report

**Course:** AIGC 5604 — Applied AI for Digital Arts · Spring/Summer 2026
**Assessment:** Capstone Project (30% course weight)
**Track:** Individual · **Creative Lead:** Yash Ranamagar
**Theme:** Futuristic Products · **Submission date:** August 18, 2026

**Deliverables at a glance**
- 🖼️ **Key Visual Poster** — `1_artwork_prototype/poster/Nano_Reactor_FINAL_poster.jpeg`
- 🎬 **Promotional Video Spot (30s, 1920×1080)** — `1_artwork_prototype/video/Nano_Reactor_FINAL_spot.mov` · **Watch:** https://youtu.be/n1xZHRJyDmg

---

## 1. Executive Summary
*Nano Reactor* is a speculative B2B campaign for a fictional clean-energy company. Its product, the **NR-114**, is a compact, "walk-away safe," megawatt-scale nuclear module pitched as on-site power for the data centers driving the AI boom. The campaign pairs a cinematic key-visual poster with a 30-second promotional spot, both produced through a multi-tool generative-AI pipeline under close human art direction, and fully documented for provenance, licensing, and ethics.

The core creative tension — advertising *clean energy for AI*, using *energy-intensive AI to make the ad* — is confronted directly in the reflection rather than avoided, and the project's lowest peer-review score (ethics/greenwashing) is treated as the essay's central subject.

## 2. Concept & Speculative Vision
| Element | Detail |
|---|---|
| Product | Nano Reactor **NR-114 (PWR-Class Module)** — compact nuclear power core |
| Positioning | *"Clean, compact nuclear power — a megawatt-scale plant engineered for the data centers behind the age of AI."* |
| Key specs (on artifact) | 3.2 MW continuous · Walk-away Safe · 8-yr core life · Zero operational carbon |
| Brand | `nanoreactor.io` · two-orbit atom logo |
| Inspiration (disclosed) | **Aalo Atomics** (aalo.com) for the compact-reactor concept; a **DJI poster** for background/layout mood — style references only, never copied |
| Audience | Hyperscale data-center operators, AI-infrastructure builders, energy investors, sustainability-focused enterprise buyers |

## 3. Production Pipeline & Toolchain
The work moved deliberately across tools, each chosen for a specific strength:

```
CONCEPT ──► Aalo + DJI references, Perplexity for prompt research
   │
POSTER ──► Claude Design (design system, logo, layout, editable HTML poster 1240×1754)
   │          │
   │          └─► Google Flow · Nano Banana 2 (hero reactor + 10-step cinematic refinement)
   │
VIDEO  ──► Google Flow · Nano Banana 2 (stills) ─► Veo 3.1 Lite/Fast + Omni Flash (image-to-video)
   │
AUDIO  ──► ElevenLabs (Kal Jones voiceover) + Suno (Horizon Ignition music)
   │
EDIT   ──► DaVinci Resolve (cut, sequence, color, sync) ─► 30s spot ─► YouTube
```

| Tool | Model | Role |
|---|---|---|
| Claude Design | — | Design system (132 tokens, 14 components, 23 cards), two-orbit atom logo, editable HTML poster |
| Google Flow | Nano Banana 2 | All poster imagery + hero reactor + atom/video stills |
| Google Flow | Veo 3.1 Lite / Veo 3.1 Fast / Omni Flash | Image-to-video animation of 22 clips |
| ElevenLabs | Eleven Multilingual v2 | Voiceover (final voice: Kal Jones) |
| Suno | v4.5-all | Background music (instrumental) |
| DaVinci Resolve | — | Human video edit & assembly |
| Perplexity | — | Prompt-engineering research aid (no deliverable asset generated) |

## 4. Prompt Engineering & Iteration
**28 prompts** are logged and analyzed in `2_data_templates/prompt_refinement_log.csv` (Individual minimum: 5–7). Highlights of the iteration discipline:

- **Hero reactor** was image-referenced from Aalo, then refined ("make it more cylindrical… match the reference") — human-directed convergence, not a single lucky roll.
- **Poster** went through a 10-step conversational refinement in Nano Banana 2: cinematic DJI-style redesign → spec-callout sizing → 4K upscale → resize to 1240×1754 → **peer-driven typo fix** → bolder eyebrow → logo swap.
- **Video** used a consistent **image → video** method: generate a still, then animate it. Prompts were heavily art-directed with negative prompts (e.g., cooling framed as *"calm controlled thermal management rather than danger… no sparks, no warning signals"*).
- **Seed control:** Nano Banana 2 and Veo do not expose seeds; consistency was instead maintained by editing a single evolving composition (documented, not left blank).
- **Voiceover** required a **pronunciation script** — "NR-114" rewritten as "N. R. one one four," with punctuation added to control pacing.

Every logged prompt carries a source link; the full step-by-step trail is in `2_data_templates/source_history_links.md`.

## 5. Provenance & Reproducibility
`2_data_templates/provenance_seed_log.csv` tracks **39 assets** — filename, tool, model, prompt reference, parameters, date, human edits, final use, and a source link per asset. The two-tier system (complete asset inventory + curated analyzed prompts + a full-link appendix) makes the work reproducible without bloating the logs.

## 6. Human Creative Control & Editing
The AI produced raw material; the authorship is human:
- Concept, references, and the design system's structure
- Selection among dozens of iterations; the hero's final form; typography and spec messaging
- The **DaVinci Resolve** edit — all Veo clips + Suno music + Kal Jones VO imported, cut into beats, sequenced, color-managed, and synced by hand into the 30-second spot
- The prompts themselves as authored artifacts (negative prompting, art-direction constraints)

## 7. Peer Review & Evidence-Based Revision
Presented as the **Phase-1 Alpha Prototype** (poster) at the in-class showcase. Five reviewers scored five criteria (`2_data_templates/peer_feedback_prototype6_RAW.csv`):

| Criterion | Avg (1–5) |
|---|---|
| Concept | 4.60 |
| Craft | 4.60 |
| Accessibility | 4.10 |
| Originality | 4.00 |
| **Ethics** | **3.60** (lowest) |

**Documented evidence-based revision (Individual requires 1):** Reviewer r3 flagged distorted/misspelled bottom text — *"N2-114"* and *"nanozeactor.io."* This drove logged prompt **P10** (*"change nanozeactor.io to nanoreactor.io"*) plus spec-text enlargement. Before/after is evidenced in `2_data_templates/peer_review_revision_log.csv`, with the final poster reading correctly as **NR-114 / nanoreactor.io**.

## 8. Ethics, Licensing & Critical Reflection
Full essay: `4_notes_reflection/critical_reflection.md`. Audit: `2_data_templates/ethical_licensing_audit.csv` (11 items). Key positions:

- **Copyright:** No source image was copied — Aalo/DJI were style/concept references, disclosed openly; final imagery was AI-regenerated.
- **Licensing (honest limit):** the **Suno music was made on a free plan that does not grant commercial rights** — acceptable for this non-commercial academic exercise, disclosed transparently; a real release would need a paid plan or replacement. Other tools marked "to verify."
- **Bias:** the models' default "premium tech-ad" aesthetic surfaced (reviewers noted an "Apple-ad" familiarity); mitigated by human curation, acknowledged as not fully escaped.
- **Deepfakes:** the voiceover is a **synthetic stock voice, not a clone of a real person** — no likeness/consent harm.
- **Environment:** the campaign's own thesis (AI's power demand outpaces its infrastructure) mirrored the project's own compute footprint; iteration discipline is framed as an environmental practice.
- **Greenwashing:** the peer critique of unqualified "clean/zero-carbon/walk-away safe" claims is accepted; claims are labeled speculative/fictional throughout.

## 9. Repository Map
```
Capstone/
├── README.md                          Portfolio index → rubric
├── Nano_Reactor_Portfolio_Report.md   ← THIS report
├── 1_artwork_prototype/               Final poster + final 30s video (what is judged)
├── 2_data_templates/                  Prompt log, provenance, ethics audit, peer review, link appendix
├── 3_output_resource/                 22 clips · 5 audio · poster iterations · logo · reference
└── 4_notes_reflection/                Creative brief · AI tool disclosure · critical reflection essay
```

## 10. Assessment Alignment (100 pts)
| Component | Pts | Where evidenced |
|---|---|---|
| Creative Concept & Final Artifact | 20 | `1_artwork_prototype/` |
| Technical & Effective Use of AI | 15 | `2_data_templates/` + `3_output_resource/` |
| Human Editing & Creative Control | 20 | `3_output_resource/` + DaVinci edit |
| Process Documentation & Provenance | 20 | `2_data_templates/` (28 prompts, 39 assets) |
| Ethical Reflection & Critical Awareness | 15 | `4_notes_reflection/` |
| Prototype, Peer Evaluation & Revisions | 10 | peer review + traced revision |

---
*Appendix — full tool disclosure: `4_notes_reflection/ai_tool_disclosure.md`. All prompt source links: `2_data_templates/source_history_links.md`.*

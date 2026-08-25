# Nano Reactor — an AI-Creation Provenance Case Study

**A worked example of doing generative-AI creative work *transparently*** — with a full audit trail of tools, prompts, versions, licenses, and human decisions behind every asset.

This repo is two things at once:
1. 🎨 **A capstone portfolio** — a speculative campaign ("Nano Reactor") made almost entirely with generative AI.
2. 🧭 **A reusable method** — how to keep provenance, licensing, and ethics records for *any* AI-assisted project.

> 🧭 **The reusable how-to:** [`PROVENANCE_METHOD.md`](PROVENANCE_METHOD.md) + blank templates in [`provenance-toolkit/`](provenance-toolkit/)
> 📄 **The full write-up:** [`Nano_Reactor_Portfolio_Report.pdf`](Nano_Reactor_Portfolio_Report.pdf) · [`.md`](Nano_Reactor_Portfolio_Report.md)
> ▶ **Watch the 30s spot:** https://youtu.be/n1xZHRJyDmg

---

## Why this exists
With today's tools, "original" and "synthetic" sit on a thin line. **Provenance is the chain of custody** — where an asset came from, what made it, and which choices were human. Industry is formalizing this (C2PA / Content Credentials); this repo is the human-readable, do-it-by-hand version, shown end-to-end on a real project.

Transparency here is deliberate — including the awkward parts (a non-commercial music track; peer critique of "greenwashing" claims). Honesty *is* the demonstration.

## Repository structure

| Folder / file | Contents |
|---|---|
| **`PROVENANCE_METHOD.md`** | The reusable method — start here to apply it yourself |
| **`provenance-toolkit/templates/`** | Blank CSV templates you can copy into your own project |
| **`1_artwork_prototype/`** | Final deliverables — poster + video (video linked, not committed) |
| **`2_data_templates/`** | The audit trail: prompt/iteration log, provenance log, licensing & ethics audit, peer-review→revision log, source-link appendix |
| **`3_output_resource/`** | Production pipeline: logo, poster source (heavy raw media is linked, not committed) |
| **`4_notes_reflection/`** | Creative brief, AI tool disclosure, critical reflection essay |

## What's in the audit trail (`2_data_templates/`)
- `prompt_refinement_log.csv` — **28** logged & analyzed prompts, each with source link
- `provenance_seed_log.csv` — **39** assets (tool, model, params, human edits, source link)
- `ethical_licensing_audit.csv` — **11** audited items (incl. inspiration-source disclosure)
- `peer_review_revision_log.csv` — 5 reviewers → a traced, evidenced revision
- `source_history_links.md` — the full step-by-step link trail

## Tools used
- **Poster:** Claude Design (design system, logo, layout) → Google Flow · **Nano Banana 2** (imagery, hero reactor, 10-step refinement)
- **Video:** Google Flow · Veo 3.1 Lite/Fast + Omni Flash (image-to-video, 22 clips)
- **Voiceover:** ElevenLabs (Eleven Multilingual v2, "Kal Jones") · **Music:** Suno (v4.5-all)
- **Edit:** DaVinci Resolve · **Prompt research:** Perplexity
- **Inspiration (disclosed, not copied):** Aalo Atomics (product) · a DJI poster (layout)

## License & rights
Mixed, and honest about it (see [`LICENSE`](LICENSE)):
- **Method, docs, templates, logs** → CC BY 4.0 (reuse freely with credit)
- **AI-generated assets** → academic demonstration only, *not* openly licensed (rights governed by each tool's ToS; music is non-commercial)
- **Third-party references** → not redistributed; linked by URL only

*AIGC 5604 — Applied AI for Digital Arts · Capstone · Yash Ranamagar · 2026. Not legal advice.*

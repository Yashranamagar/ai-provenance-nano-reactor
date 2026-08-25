# How to Keep an AI-Creation Audit Trail
### A reusable provenance & ethics method — as used in the *Nano Reactor* project

> **What this is:** a simple, copy-pasteable system for recording *how* AI-assisted work was made — the tools, prompts, versions, references, licenses, and human decisions — so the process is transparent and the origin of every asset is traceable.
>
> **Why it matters:** with today's tools, "original" and "synthetic" sit on a thin line. Provenance is the **chain of custody** that says where a thing came from and who made which choices. The tech industry is formalizing this with standards like **C2PA / Content Credentials** (cryptographic "where did this come from" metadata). This method is the human-readable, do-it-by-hand version of the same idea — usable on any project, with any toolchain.

---

## The core idea in one line
**Record as you create, not after** — every asset gets a paper trail covering *tool → model/version → prompt & settings → source references → license → human edits → final use.*

## What provenance does (both directions)
1. **Outward / respect:** proves you honored other people's rights — licenses, and the line between *inspiration* and *copying*.
2. **Inward / authorship:** evidences **your** human contribution (selection, arrangement, editing) — the part that's actually yours.
3. **Authenticity:** lets anyone verify the origin of a synthetic asset instead of guessing whether it's real.

> ⚠️ **Necessary, not sufficient.** An audit trail makes you *accountable* for your choices; it doesn't make bad choices good. A logged greenwashing claim is still a greenwashing claim. The ethics live in the choices — the log just makes them checkable.

---

## The 4 core records (+ 3 supporting docs)
Each is a plain CSV or Markdown file. Blank templates are in [`provenance-toolkit/templates/`](provenance-toolkit/templates/).

### 1. Provenance / Asset Log — *"what exists and how was it made"*
One row per asset. Columns:
`asset_id, filename, asset_type, tool, model_version, prompt_ref, seed, key_parameters, date_created, human_edits, final_use, source_link`
- `prompt_ref` links to the prompt log; `seed`/`key_parameters` capture reproducibility (write **"n/a — conversational editor"** honestly if the tool exposes no seed).

### 2. Prompt & Iteration Log — *"the thinking, shown"*
One row per meaningful prompt. Columns:
`prompt_id, date, stage, asset_target, tool, model_version, prompt_text, key_parameters, seed, iteration_note, what_changed_and_why, outcome, source_link`
- Don't log *every* click. Log the **milestones** that show iteration and *why* each change was made. Quality of the "what changed & why" beats quantity.

### 3. Licensing & Ethics Audit — *"can I use this, and is it responsible"*
One row per asset/source. Columns:
`item_id, asset, asset_type, origin, tool_used, license_type, commercial_use_ok, attribution_required, ai_content_disclosed, copyright_bias_notes`
- Record the **plan/tier** you were on (free vs paid changes your rights). Flag deepfake/likeness, bias, and greenwashing honestly.

### 4. Feedback & Revision Log — *"what I heard and what I changed"*
One row per feedback item. Columns:
`review_id, phase, date, reviewers, asset_reviewed, criterion, avg_score, feedback_summary, action_taken, evidence_before, evidence_after, revision_confirmed`
- The gold standard is a **traceable revision**: feedback → a specific change → before/after evidence.

### Supporting docs
- **Source-history appendix** (`source_history_links.md`): every share link, mapped to its asset. This is the "full trail" tier so the logs stay curated.
- **AI tool disclosure**: one table of every generative tool + what it produced.
- **Critical reflection**: the honest essay — copyright, bias, synthetic media, environmental cost, human control.

---

## Step-by-step workflow
1. **Before you generate:** note your references and *why* (inspiration ≠ copying). Save reference links, not necessarily the files (see rule below).
2. **Each meaningful generation:** log the prompt, tool, model/version, key settings, and the share link. Name the output file descriptively.
3. **Each edit/curation:** record what you changed by hand and why.
4. **When an asset is final:** mark `final_use` and confirm its license.
5. **After feedback:** log it, act on it, and capture before/after.
6. **At the end:** write the disclosure table + reflection. Keep a two-tier trail: **complete asset inventory + curated analyzed prompts + full link appendix.**

## Rules of thumb
- **Link third-party references — don't redistribute them.** Keep copyrighted source images *out* of a public repo; store the URL in the log instead. (This repo `.gitignore`s its `reference/` folder for exactly this reason.)
- **Tool + model + version + settings**, every time. "Made with AI" is not provenance.
- **Note the license per asset**, including free-vs-paid tier limits.
- **Record human edits** — they're the evidence of your authorship.
- **Disclose, don't hide, the awkward parts** (a non-commercial track, a shaky claim). Honesty *is* the demonstration.

## How to reuse this
1. Copy [`provenance-toolkit/templates/`](provenance-toolkit/templates/) into your project.
2. Fill rows *as you work.*
3. Adapt columns to your medium — the four record types generalize to image, video, audio, music, code, writing.

---
*Method extracted from the AIGC 5604 capstone "Nano Reactor." Reuse freely (see `LICENSE`). Not legal advice — for commercial use, confirm each tool's Terms of Service.*

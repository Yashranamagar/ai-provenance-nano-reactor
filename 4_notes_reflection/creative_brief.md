# Creative Brief — "Nano Reactor" Campaign

**Course:** AIGC 5604 — Applied AI for Digital Arts · Capstone (Spring/Summer 2026)
**Track:** Individual
**Creative Lead:** Yash Ranamagar
**Campaign theme (from brief):** Futuristic Products

---

## 1. The Product
**Nano Reactor — NR-Series (NR-114 PWR-Class Module)**
A clean, compact, megawatt-scale nuclear power plant engineered to power the data centers behind the age of AI.

**Key selling points (as shown on the poster):**
- **3.2 MW** continuous output
- **Walk-away Safe** (passive safety)
- **8-year** core life
- **Zero** operational carbon
- Brand handle: `nanoreactor.io`

## 2. The Big Idea / Positioning
AI's exploding compute demand needs enormous, clean, reliable power — delivered on-site. Nano Reactor positions compact nuclear as the invisible engine of the AI era: *"Clean, compact nuclear power — a megawatt-scale plant engineered for the data centers behind the age of AI."*

## 2a. Inspiration & Research
- **Product concept** inspired by **Aalo Atomics** (https://www.aalo.com/) — a real compact-reactor company; used for the speculative product framing and hero-object form.
- **Visual layout / background** inspired by a **DJI product poster** (https://www.pinterest.com/pin/8585055532544025/); reference saved in `3_output_resource/reference/`. Used as style reference only — the final background was AI-regenerated.

## 2b. Poster Production Pipeline (how it was actually made)
1. **Claude Design** — built the full **Nano Reactor Design System** (132 tokens, 14 components, 23 design cards, Console + Marketing UI kits), iterated the **two-orbit atom logo**, and assembled the poster (portrait 1240×1754) as an editable HTML layout — the four specs (3.2 MW, 8 yr, Walk-away safe, Zero carbon) set as live 38px text overlays with Lucide icons over the cinematic image plate. Exported to PDF (`ClaudeDesign_poster_source.pdf`) and Canva.
2. **Google Flow (Nano Banana 2)** — cinematic DJI-style redesign, made the **hero reactor** (Aalo-inspired) stand out, then refined spec sizing across ~6 conversational iterations.
3. **Google Flow (Nano Banana 2)** — 4K upscale → resized to submission spec (1240×1754) → **peer-driven fix** (nanozeactor.io → nanoreactor.io) → bolder eyebrow → swapped in the Claude Design logo → **final poster**.

Full ordered prompt trail: `2_data_templates/source_history_links.md` and `prompt_refinement_log.csv`.

## 3. Target Audience
Hyperscale data-center operators and AI infrastructure builders; energy/infrastructure investors; sustainability-focused enterprise buyers weighing clean on-site power for compute-heavy facilities.

## 4. Tone & Visual Language
- Cinematic, premium-tech, cool blues + warm horizon light
- Product-hero framing; clean speculative typography; minimal spec callouts
- Motion: drone approaches, server aisles, reactor core powering up, energy pulses through a city

## 5. Deliverables (Individual track)
- [x] **Key Visual Poster** — `1_artwork_prototype/poster/Nano_Reactor_FINAL_poster.jpeg`
- [x] **Promotional Video Spot (30s, 1920×1080)** — `1_artwork_prototype/video/Nano_Reactor_FINAL_spot.mov` (edited in DaVinci Resolve from Google Flow clips + Suno music + ElevenLabs VO) · **Watch:** https://youtu.be/n1xZHRJyDmg

## 6. Soundtrack & Voice
- **Music:** `Horizon Ignition.mp3` — Suno (v4.5-all), instrumental, "cinematic, industrial, sci-fi" — https://suno.com/s/HaPD80oWOXjlTFs0
- **Voiceover:** ElevenLabs (Eleven Multilingual v2) — auditioned Louis, Jackson, Kal Jones; **final = Kal Jones** (Deep, Smokey and Reliable)
- **VO script (as narrated):**
  > A.I. is scaling faster than the infrastructure built to power it.
  > Every model, Every data center, Every breakthrough… demands continuous power.
  > Meet, The next generation, Of industrial energy.
  > Introducing… The Nano Reactor, N. R. one one four.
- **Process note:** the script was rewritten into a *pronunciation script* so the model would enunciate correctly — e.g. "NR-114" spelled out as "N. R. one one four", with added periods/ellipses to control pacing and emphasis.

## 6a. Edit (DaVinci Resolve)
All Veo clips + the Suno music bed + the Kal Jones voiceover were imported into **DaVinci Resolve**, cut into short beats, sequenced, and synced by hand — the assembly and timing are human-authored.

## 7. Production Timeline (from file history)
- **Aug 10:** Claude Design template → Google Flow background/hero iterations
- **Aug 10–12:** poster refinement iterations
- **Aug 11:** Alpha Prototype (poster) presented at in-class showcase; peer review collected
- **Aug 14:** voiceover takes generated (ElevenLabs)
- **Aug 17:** music track (Horizon Ignition)
- **Aug 18:** video clips generated; final poster resized/corrected in Google Flow (`...202608182014` → FINAL)

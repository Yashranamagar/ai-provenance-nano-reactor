# AI Tool Disclosure

Full disclosure of every generative-AI tool and reference source used, per the assignment's provenance requirement.

## Inspiration / research sources (not reproduced in final work)
- **Aalo Atomics** — https://www.aalo.com/ — primary conceptual inspiration for the *Nano Reactor* compact-reactor product and hero-object form.
- **DJI poster** (Pinterest) — https://www.pinterest.com/pin/8585055532544025/ — layout/background aesthetic inspiration. Reference stored at `3_output_resource/reference/DJI_poster_reference_pinterest.jpeg`. Style inspiration only; the final background was AI-regenerated, not the DJI image itself.

## Generative tools used

| Stage | Tool / Platform | Model | What it produced | License basis |
|---|---|---|---|---|
| Design system, poster layout, logo, copy | **Claude Design** (Anthropic) | — | "Nano Reactor Design System" (132 tokens, 14 components, 23 design cards, Console + Marketing UI kits), two-orbit atom logo, editable HTML poster (1240×1754) → `ClaudeDesign_poster_source.pdf`, also sent to Canva once | To verify (non-commercial academic use) |
| Poster imagery: cinematic redesign, hero reactor, spec sizing, 4K upscale, resize-to-spec, typo/logo fixes | **Google Flow** | **Nano Banana 2** | Final poster + iterations (see `source_history_links.md`) | To verify (non-commercial academic use) |
| Video clips | **Google Flow** | **Veo 3.1 - Lite**, **Veo 3.1 - Fast**, **Omni Flash** (image-to-video) | 22 speculative clips — Nano Banana 2 stills generated in Flow, then animated | To verify (non-commercial academic use) |
| Voiceover | **ElevenLabs** | Eleven Multilingual v2 | Narration — final voice **Kal Jones** (Speed 1.1 / Stability 50 / Similarity 75 / Style 45 / Speaker boost on); Louis & Jackson auditioned | To verify (non-commercial academic use) |
| Music | **Suno** | v4.5-all | `Horizon Ignition.mp3` — instrumental, style "cinematic, industrial, sci-fi" | ⚠️ FREE plan = **NOT commercial**; non-commercial academic use only |
| Editing / compositing | **DaVinci Resolve** | — | Video assembly, cut, color, timing | N/A (human tool) |
| Prompt-engineering aid | **Perplexity** | — | Researched & refined how to phrase image and video generation prompts (not used to generate any deliverable asset) | N/A (research assistant) |
| Documentation assistant | Claude (Anthropic) | claude-opus-4-8 | Portfolio structuring, provenance logs, prompt extraction | N/A |

> **Note on "seed control":** Nano Banana 2 is a *conversational image editor* and does not expose a seed parameter. Visual consistency across the ~10 poster iterations was maintained by **iteratively editing one evolving composition** (image-conditioned edits) rather than re-rolling seeds — the reproducibility trail is the ordered prompt history in `source_history_links.md`.

## Human creative-direction statement
Every AI output was directed, curated, and post-processed by the creative lead. Claude Design set the compositional template; Google Flow (Nano Banana 2) generated and refined the imagery across ~10 logged iterations; Google Flow (Veo) animated the clips; the human made all art-direction decisions — concept, reference selection (Aalo, DJI), hero design, iteration selection, spec messaging, resizing, and the peer-driven spelling/logo corrections.

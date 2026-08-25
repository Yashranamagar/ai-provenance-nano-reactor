# Source-History Links (full reproducibility appendix)

The `prompt_refinement_log.csv` summarizes the milestone prompts; these links hold the full
step-by-step trail for anyone reproducing the work.

## Final deliverables
- **Final video spot (YouTube):** https://youtu.be/n1xZHRJyDmg
- Final video file: `1_artwork_prototype/video/Nano_Reactor_FINAL_spot.mov` (30s, 1920×1080)
- Final poster: `1_artwork_prototype/poster/Nano_Reactor_FINAL_poster.jpeg`

## Hero reactor object — Google Flow (Nano Banana 2)
Image-referenced from the Aalo reactor:
1. Reactor hero design — https://labs.google/fx/tools/flow/shared/image/36dcecfd-6292-4bd2-a48a-856f9eaf20d1
2. Refine to cylindrical / match reference — https://labs.google/fx/tools/flow/shared/image/b6a2848d-7ec5-48f5-9ae5-daa01bf490fc

## Poster — Google Flow (model: Nano Banana 2)
Iterative conversational edits on a locked base image (Nano Banana 2 does not expose seeds;
consistency was maintained by editing one evolving composition rather than re-rolling seeds):

1. Cinematic DJI-style redesign — https://labs.google/fx/tools/flow/shared/image/9af1fbd7-9579-4cef-87a4-9d8de4dfa7a9
2. Enlarge side features — https://labs.google/fx/tools/flow/shared/image/39a696fc-4185-4777-8df9-49cd4e6d5016
3. Enlarge feature font — https://labs.google/fx/tools/flow/shared/image/dbfced10-e6f9-4952-a8dd-9eaa2ed8f3a5
4. Fine-tune feature size — https://labs.google/fx/tools/flow/shared/image/c4710fc4-e3ab-435c-a666-6c34b778954b
5. Upscale to 4K — https://labs.google/fx/tools/flow/shared/image/57198e28-9325-4193-9824-53d2e197d981
6. Resize to 1240×1754 (submission spec) — https://labs.google/fx/tools/flow/shared/image/22b5fe28-8607-4f2e-8441-965f2ea7b420
7. **[peer-driven]** Fix typo nanozeactor.io → nanoreactor.io — https://labs.google/fx/tools/flow/shared/image/dfab6c85-c4f8-4106-a74e-fe665eb5200e
8. Bolder NR-SERIES eyebrow — https://labs.google/fx/tools/flow/shared/image/5d133710-1ceb-4243-bc15-372bd2051846
9. Bolder eyebrow + replace logo with provided brand mark — https://labs.google/fx/tools/flow/shared/image/c209f54c-f892-47dd-8e2d-b560d1411fb4

- **Claude Design (layout/template/logo/copy):** https://claude.ai/design/p/7aa1f821-933e-4f9c-a28d-d1d66fd5b66f?via=share

## Video — Google Flow (Veo 3.1 - Lite, image-to-video)
Workflow: generate a still in Flow (Nano Banana 2), then animate it (Veo 3.1 - Lite).

### Thread 1 — Atom → nuclear fission (→ Untitled_Scene...202608181642.mp4)
Atom stills:
1. Cinematic atom — https://labs.google/fx/tools/flow/shared/image/0910f556-e7fd-4479-831c-7179d04f5a44
2. Deep black-space background — https://labs.google/fx/tools/flow/shared/image/869931cc-431d-4f94-a65d-0c1da547d27a
3. Irregular/flowy aura — https://labs.google/fx/tools/flow/shared/image/91438934-9635-41c4-ab9d-e557b6ecea24
4. More irregular rings + aura (final still) — https://labs.google/fx/tools/flow/shared/image/59cd9c63-f7da-4d25-85a7-f792e84f1c23

Video:
- Atom fission split — https://labs.google/fx/tools/flow/shared/video/6787f5b7-6d7a-45e4-a610-89833c68a4f6

### Thread 2 — Data center (shared establishing stills)
- Stills: https://labs.google/fx/tools/flow/shared/image/103a3b2b-1ca3-41f0-af62-8b5032a063fd · https://labs.google/fx/tools/flow/shared/image/c45d737e-4de0-4f79-8911-1477a66650c5 · https://labs.google/fx/tools/flow/shared/image/968b5c28-4ddc-4825-9452-422e0347f5fd

### Per-clip image → video links (folder name → sources)
- **Truck_moving_left_...1641** — video https://labs.google/fx/tools/flow/shared/video/d2434523-3f4a-427c-bed9-d207a7c600d6
- **Reactor_housing_product_shot_...1644** — video https://labs.google/fx/tools/flow/shared/video/fd5d2b02-4b0c-4549-9be5-d989dbc2e74e
- **Reactor_energy_core_powering_up_...1642** — video https://labs.google/fx/tools/flow/shared/video/950e0a43-a7f4-4c5b-9a54-a6c98f0cb468
- **Reactor_core_powering_up_...1642** — video https://labs.google/fx/tools/flow/shared/video/d6d48708-9af0-4c72-89e2-8bf82758166d
- **Reactor_cooling_vent_emitting_vapor_...1644** — video https://labs.google/fx/tools/flow/shared/video/66cd3b8f-8345-40a4-807a-723422e30853
- **Reactor_components_assembling_...1642** — stills https://labs.google/fx/tools/flow/shared/image/21e6a9da-a2f2-4df9-af77-e15acd77151b · https://labs.google/fx/tools/flow/shared/image/2c8703a8-b6fe-435a-865a-c322a708c4e9 · https://labs.google/fx/tools/flow/shared/image/80e2bb2e-662d-4ade-acfc-074fb6623437 ; videos https://labs.google/fx/tools/flow/shared/video/1a812a5f-ad41-4f8e-abef-cc8ea9cf06bd · https://labs.google/fx/tools/flow/shared/video/83763633-ce62-4608-ad38-6965f94677c7 · https://labs.google/fx/tools/flow/shared/video/38ed35ce-f0cc-40b8-b571-ee3b292099d7
- **Modular_reactor_housing_product_...1644** — video https://labs.google/fx/tools/flow/shared/video/70e77a48-23ca-43f4-8853-35dbc0950f51
- **Hero_object_silhouette_color_reveal_...1800** — stills https://labs.google/fx/tools/flow/shared/image/68301b4a-874f-43b3-aa3c-82b664d5cb0b · https://labs.google/fx/tools/flow/shared/image/8a50eea2-d64d-4099-b81b-4ea6f8cb5704 ; video https://labs.google/fx/tools/flow/shared/video/06e15a18-7e11-4eee-abfa-1821424c384e
- **Energy_pulses_moving_through_city_...1643** — stills https://labs.google/fx/tools/flow/shared/image/05df7afe-c407-45c6-ad31-0f13320dfd11 · https://labs.google/fx/tools/flow/shared/image/24119271-b6a1-4201-99cd-fc2d1b1adc50 ; video https://labs.google/fx/tools/flow/shared/video/b3431406-ad1e-48bb-bb3f-73098ed69000
- **Drone_approaching_future_data_ce_...1227** — stills https://labs.google/fx/tools/flow/shared/image/4f7627ba-a427-4412-9677-04d98cad4128 · https://labs.google/fx/tools/flow/shared/image/e6cefd26-bf71-40e5-bd0e-08a8f95f1927 ; video https://labs.google/fx/tools/flow/shared/video/65dca981-c6df-4278-bef0-7b10f18cafc8
- **Drone_flying_over_building_...1251** — video https://labs.google/fx/tools/flow/shared/video/1a1ad63f-98cd-47b1-baf1-ebb4b9080eb8
- **Data_center_illuminating_at_night_...1250** — video https://labs.google/fx/tools/flow/shared/video/b95cf1cc-ad81-4157-a0de-bd888528b266
- **Create_closing_statement_video_...1933** — videos https://labs.google/fx/tools/flow/shared/video/51bb1f90-14e4-46d2-937f-53d00603e66b · https://labs.google/fx/tools/flow/shared/video/ba15b5e1-73e4-49d4-b27c-eca86496f344 · https://labs.google/fx/tools/flow/shared/video/faa9b21a-35d7-4dc2-a57c-c82340366ac0
- **Cooling_fans_spinning_in_server_...1641** — video https://labs.google/fx/tools/flow/shared/video/4f92c91f-2e49-46b9-8f60-1268964cb5ec
- **Computers_in_data_center_racks_...1743** — still https://labs.google/fx/tools/flow/shared/image/52cd1a1d-ecbc-45e4-ae47-4982a250122d ; video https://labs.google/fx/tools/flow/shared/video/ec725823-a274-4f7a-81d7-985cb2b89178
- **Camera_moving_toward_computer_racks_...1741** — stills https://labs.google/fx/tools/flow/shared/image/a06d4ae4-5681-40d5-b99c-a3729bfc0aea · https://labs.google/fx/tools/flow/shared/image/57a6f667-2277-4c85-b957-117090f134e0 · https://labs.google/fx/tools/flow/shared/image/58f30c97-b7b9-442b-93e9-9d6f701b8d84 ; video link TODO (the pasted video URL duplicated a still — resend if you want the motion prompt logged)
- **Camera_moving_down_server_aisle_...1642** — video https://labs.google/fx/tools/flow/shared/video/64a72df5-60ac-4dcc-a675-7e90bada8a5d
- **Camera_moves_to_reveal_profile_...1828** — stills https://labs.google/fx/tools/flow/shared/image/8310fcb5-4daf-492f-aba7-8f0e391774f0 · https://labs.google/fx/tools/flow/shared/image/8c06d0ca-98e3-4e5b-a017-95ce8dd09452 · https://labs.google/fx/tools/flow/shared/image/7211810e-399c-40ca-8ea2-93df426a8a18 ; video https://labs.google/fx/tools/flow/shared/video/4e11926f-de67-4f7c-b145-c6798f1ce84a

## Audio
- **Voiceover — ElevenLabs** (Eleven Multilingual v2): final voice = **Kal Jones** (Deep, Smokey and Reliable); Louis & Jackson auditioned. Settings: Speed 1.1 / Stability 50 / Similarity 75 / Style 45 / Speaker boost on.
- **Music — Suno** (v4.5-all, instrumental, "cinematic, industrial, sci-fi"): https://suno.com/s/HaPD80oWOXjlTFs0

## Reference sources (inspiration only, not reproduced)
- Aalo Atomics — https://www.aalo.com/
- DJI poster (background inspiration) — https://www.pinterest.com/pin/8585055532544025/

# UnspokenSmiles VR Training

A prototype VR training experience offered to the **Unspoken Smiles Foundation** — a working demo you can play, not their official product.

**Demo only. Not official, not endorsed, not affiliated with Unspoken Smiles.** No partnership, pilot, or endorsement has been agreed, and no contact has been made. The prototype is the pitch: try it, tell us what is wrong, decide whether to pilot it.

## What this is

A browser-based 3D dental training world (Three.js, IWSDK patterns) built for the NemulAI × Hack District hackathon, **Impact track**:

- **One fully playable session: Prevention & School Screening** — 9 steps, lesson → checklist → tasks → visual quiz, Bronze to All-Star ratings
- A 3D clinic world with 4 districts, Coach Mira, a 5-step quest, and collectibles
- A Simulation Studio run: brief + 5 decisions scored 2/1/0, consequence, debrief + portable run record
- A searchable catalogue of the SmartCiti.X inventory: 37 stations with skill mappings, 6 games, 16 eggs
- A full wiki: module list, dental skill registry, LearnerProgressEvent contract, IWSDK stack with IWER / Quest plan, equipment-to-spec tables, licensure bridge

## Run it

Open `index.html` in a browser (or serve this repo with GitHub Pages). No headset needed — magic-window desktop mode works; a WebXR session is offered on Quest when one is available.

## Roadmap

`docs/unspokensmiles-vr-roadmap.pdf` — 13-page roadmap: what the prototype demonstrates, the website/social and git review, the proposed project, equipment to spec, licensure-ready pathways, the pilot offer, and Phases 0–6.

## Research

`docs/research-and-training-guides-2026-11-07.md` — Firecrawl research notes: Unspoken Smiles homepage / About / Zero Cavity pages, CDC Guidelines for Infection Control in Dental Health-Care Settings 2003 (MMWR 52(RR17)), DANB CDA from danb.org (RHS + ICE + GC, $450, 60-day window, 195 minutes, 245 questions, Pathways I–III), and California RDA from the Dental Board of California (800-hour program breakdown).

## Licensure — read this first

**This app cannot licence users.** Licensure is external only: CODA-accredited program, state board, DANB CDA, NBDHE, state X-ray certification. The app is licensure-*ready* / exam-prep only. VR practice ≠ clinical hours. Simulation ≠ certification. XP, badges, and completed runs are never a credential or completion record.

## Honest gaps

- The deep walkthrough video is **not recorded yet** — storyboard + guide images only. Recording is a CleanShot X task on a Mac.
- Lab bench equipment specs are flagged "to be confirmed" — no manufacturer datasheet was found, so no numbers were invented.
- The Costa Rica assistant/hygienist pathway is **unverified** — CCDCR and ULACIT were not checked directly, so it is not presented.
- Conflicting published numbers are quoted with sources and never merged (founded 2014 vs 2011; 9,000+ vs 10,000+ children served; 21 vs 40 fellows in 2025).
- The full IWSDK scaffold (@iwsdk/core) is not dropped into this build; the app applies IWSDK's architecture (grab, locomotion, spatial UI, dual-runtime) over Three.js and says so honestly.

## Sources

- Unspoken Smiles Foundation: https://www.unspokensmiles.org/
- DANB: https://www.danb.org/exams/exam/cda-exam
- CDC MMWR 2003;52(RR17): https://www.cdc.gov/MMWR/preview/mmwrhtml/rr5217a1.htm
- Dental Board of California: https://dbc.ca.gov/formspubs/app_rda_provider_rda.pdf
- Meta Immersive Web SDK: https://developers.meta.com/vr/develop/iwsdk/

# UnspokenSmiles VR — Firecrawl research data + training guides

Scraped 2026-11-07 with Firecrawl (custom.firecrawl, verified working). Each scrape: success true, status 200, 1 credit. Total Firecrawl credits used in this chat today: 7 (1 test example.com + 6 content scrapes). SerpAPI was still HTTP 401 in this chat at the same time, so all findings below are Firecrawl + browser.search, not SerpAPI.

Demo-only label throughout: this is a prototype inspired by Unspoken Smiles' public work — not official, not endorsed, not affiliated. No partnership, no licence claim.

## 1. Unspoken Smiles Foundation — homepage

- Source: https://www.unspokensmiles.org/ — scrapeId 01a1b7c9-6606-741b-9ac6-6b3c9137c657
- "3.58 BILLION — Nearly half the world's population suffers from oral disease."
- Core work: school-based oral-health education; Fellowship for sustainable careers in dentistry; access to care.
- "We have helped bring healthier smiles to over 10,000 children in 9 countries across 4 continents — Haiti, India, Romania, El Salvador, Guatemala, Iraq, the Dominican Republic, Costa Rica, and the United States." Focus now Costa Rica, eventually the whole American Hemisphere.
- Homepage counters render as 0 (Oral Hygiene Kits Distributed 0k+, Children Served 0, Fellows by 2030 0, LATAM Countries 0) — do not cite counter values.
- "8 YEARS OF SUSTAINABLE IMPACT" is stale on its face — do not cite as current.
- New since earlier review: Jean Paul Laurent, Founder and CEO, Named 2026 Presidential Leadership Scholar (January 9, 2026).
- IADS partnership post June 12, 2024; Dr. Alexei Carrillo appointed to board October 2, 2023.
- Site's own headings render as "UNSPOOKEEN SMILES" (template typo — do not copy as the name).

## 2. About

- Source: https://unspokensmiles.org/about/ — scrapeId 01a1b7ca-f652-728d-85ef-9c72d8d9f445
- Mission: "To promote both long-term oral health care and economic security in the world's most disadvantaged regions."
- Vision: children enjoy healthy, happy smiles, free of oral disease and related health complications.
- History: after the 2010 earthquake in Haiti, Jean Paul Laurent, then a student at NYU School of Dentistry, returned to provide free dental care and supplies; founded the Foundation from that pilot.
- About page says "serving over 9,000+ children in 9 countries across 4 continents" — CONFLICTS with homepage "over 10,000 children". Quote with source + page, never merge.
- No founding year on the About page in the fetched text. Do not pick 2014 vs 2011 — most sources say 2014, one says March 2011.

## 3. Zero Cavity Initiative

- Source: https://unspokensmiles.org/zero-cavity-initiative/ — scrapeId 01a1b7cb-307c-7179-ae32-6f1708361835
- "We connect vetted dentistry and oral care professionals as well as Unspoken Smiles Fellows to local schools to provide free oral health screenings, education, and preventive care."
- Mission: partner with individuals, organizations, government agencies, academic institutions to implement strategies that promote dental health and minimize tooth decay in children in the Americas.
- CDC figures on the page (CDC's, not the Foundation's): approximately 20% of children and 13% of adolescents have at least one decayed tooth; tooth decay is one of the most common chronic diseases in children/adolescents in the US.
- Participation: academic institutions can implement policies so students receive a dental examination during yearly check-up; financial institutions sponsor education projects; government agencies influence policy/law; individuals/small businesses donate or raise awareness; research institutes evaluate program effectiveness.
- Pledge: commitment must be Specific, Measurable, Attainable, Timely (SMART).

## 4. Training guide — CDC infection control (primary)

- Source: https://www.cdc.gov/MMWR/preview/mmwrhtml/rr5217a1.htm — Guidelines for Infection Control in Dental Health-Care Settings — 2003, MMWR 2003;52(RR17);1-61, Kohn et al.
- Nine recommendation areas: (1) educating/protecting dental health-care personnel; (2) preventing transmission of bloodborne pathogens; (3) hand hygiene; (4) personal protective equipment; (5) contact dermatitis and latex hypersensitivity; (6) sterilization and disinfection of patient-care items; (7) environmental infection control; (8) dental unit waterlines, biofilm, water quality; (9) special considerations (handpieces, radiology, parenteral medications, oral surgery, dental laboratories).
- Key updates in 2003: standard precautions (not universal precautions); work restrictions for infected/exposed personnel; post-exposure prophylaxis for HBV/HCV/HIV; sharps-injury prevention devices; hand-hygiene products and surgical hand antisepsis; sterilization of unwrapped instruments; dental water quality (≤500 CFU/mL drinking-water standard, sterile irrigating solutions for surgery, boil-water advisories); dental radiology; aseptic technique for parenteral medications; preprocedural mouth rinsing; oral surgical procedures.
- Use as the backbone for the sterilization + infection-control stations. Cite as CDC 2003 + 2016 Summary, not as a VR mandate.

## 5. Training guide — DANB CDA (primary, resolves earlier conflict)

- Source: https://www.danb.org/exams/exam/cda-exam (scraped via Firecrawl, success true) + https://www.danb.org/ homepage.
- CDA exam = RHS + ICE + GC taken together. Fee shown on the DANB CDA page: 450 (dollars). Test window 60 days. Test time 195 minutes. Test questions 245.
- This CONFIRMS the 245-question / 195-minute figures from secondary sources and CORRECTS the earlier "~$525 total" secondary figure — use $450 as shown on danb.org, and do not quote a $75 application fee from secondary sources in-app.
- Pathways: I — graduation from a CODA-accredited dental assisting or dental hygiene program + current hands-on CPR/BLS/ACLS from a DANB-accepted provider. II — high-school graduation or equivalent + minimum 3,500 hours approved work experience + current hands-on CPR/BLS/ACLS. III — former DANB CDA status, or graduation/enrollment in a CODA-accredited DDS/DMD program, or graduation from a dental degree program outside the US/Canada, or graduation/enrollment in a post-baccalaureate program affiliated with a US/Canadian dental school on DANB's list + current hands-on CPR/BLS/ACLS.
- Official outlines linked on the page: GC Exam Outline, ICE Exam Outline, RHS Exam Outline (PDFs on danbsfprodassets.azureedge.net), plus CDA Application Packet and Candidate Handbook.
- Featured exams on danb.org: RHS, ICE, NELDA, CDA. DALE Foundation provides practice tests/review courses.
- Secondary prep sites conflict (320 questions / $270 / $450+75) — do not use them. DANB's own page is the source.

## 6. Training guide — California RDA (primary DBC source)

- Source: Dental Board of California, RDA Educational Program Application (Rev. 4/2026), https://dbc.ca.gov/formspubs/app_rda_provider_rda.pdf, via browser.search; and https://www.dbc.ca.gov/applicants/become_program_provider.shtml.
- RDA program minimum 800 hours total: 275 didactic + 260 laboratory/preclinical + 265 extramural clinical (max 20 hours clerical/administrative/practice management). RDAEF program minimum 410 hours.
- Required course hours inside the program: Radiation Safety 32h (8 didactic + 12 lab + 12 clinical), Coronal Polishing 12h (4+4+4), Pit and Fissure Sealants 16h (4+4+8), Infection Control 8h (4+2+2), California Dental Practice Act 2h. BLS may be a prerequisite, no specified minimum.
- Pathways (DBC): Board-approved RDA program (≥800h), or 15 months + ≥1,280 hours work experience, or current DANB CDA credential. All dental assistants must complete a Board-approved 8-hour infection control course before basic supportive procedures with blood/saliva exposure (BPC §1750).
- Exam: RDA Combined Written and Law and Ethics Examination. No reciprocity in California.
- Application fee $120 is from a secondary source (legalclarity.org citing DBC) — flag as secondary, verify on dbc.ca.gov before quoting in-app.

## How to use this in the VR app

- Prevention & School Screening session: Zero Cavity workflow (screen → educate → refer, no treatment in the field), CDC 20%/13% figures labelled as CDC's, SMART pledge as a debrief prompt.
- Sterilization & Operatory Setup session: CDC 2003 nine areas as the sequence spine; Class B autoclave, ultrasonic cleaner, spore test, instrument classification (critical/semi-critical/non-critical), handpieces heat-sterilised between every patient.
- Licensure bridge page: DANB CDA (245 Q / 195 min / $450 / 60-day window / Pathways I–III) and CA RDA (800h breakdown above) as external pathways with links to danb.org and dbc.ca.gov. Every page carries "VR practice ≠ clinical hours" and "simulation ≠ certification".
- Do NOT present: a founding year, a single children-served number, a DANB fee other than the $450 shown on danb.org, or any Costa Rica assistant/hygienist pathway (still unverified — CCDCR/ULACIT not checked directly).

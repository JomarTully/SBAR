ICU Handoff Report — deployable static web app

Open index.html in a browser. No installation, account, internet connection, or dependencies required.

GitHub Pages: place index.html in an icu-report folder in your existing repository. Link from your menu to icu-report/. Or upload it to a new repository root and enable Pages: main / (root).

Use dropdowns and free-text notes for the assessment. Add as many line/drain or infusion rows as needed. Generate report shows an organized report. Print / Save PDF opens your browser print dialog; choose Save as PDF to save a PDF. Save report downloads a standalone HTML report that can be opened and printed later. Save editable sheet downloads a JSON backup; Open saved sheet restores it for further editing. No entered data is transmitted or automatically stored in browser storage. Reloading or closing without a saved JSON copy loses your edits.

Use your organization's approved process for patient information and saved files. Blank fields are not normal findings. This is a handoff aid, not an EHR record, order entry tool, dose calculator, or clinical scoring engine.

Build 2026-10-03e

Neuro includes motor response and separate right/left upper/lower limb strength selections. Cardiovascular includes bilateral radial, dorsalis pedis and posterior tibial pulse selections, plus a notes field for other pulse sites. Saved sheets from the earlier version remain compatible; new fields start blank.

Neuro includes gag, cough, and separate right/left corneal reflex assessments. All start blank and appear in printed and saved reports when selected.

Labs include editable, labeled fishbone diagrams for CBC, basic metabolic panel, hepatic panel and coagulation. Additional calcium, fibrinogen and lactate fields plus separate collection-time fields are included. Enter lab values as reported; no interpretation, normal ranges or calculations are applied. Diagrams are preserved in reports and editable backups.

Fishbone fields now occupy dedicated compartments separated by gutters, preventing lines from crossing entry boxes. Each lab panel has month, day, year, hour (24-hour), and minute dropdowns. Earlier saved sample-time text remains visible until dropdowns replace it.

History dropdown: search and select multiple conditions from the supplied CONDITION DATABASE.xlsx (72 entries). Selected conditions appear in the report and editable backup. Additional history notes and older saved history remain supported. Build 2026-10-03f.

Build 2026-10-03h: lab date and time use calendar and clock pickers; shortcuts removed. Ventilator modes include PRVC and Bi-level. Selecting Bi-level shows T-high / T-low (seconds) and P-high / P-low (cmH2O) inputs. Values are saved in editable sheets and included in reports when Bi-level is selected.

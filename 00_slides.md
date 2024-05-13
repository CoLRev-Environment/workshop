---
marp: true
header: 'CoLRev workshop at ECIS 2024'
footer: 'Gerit Wagner and Julian Prester'
theme: ub-theme
paginate: true
---

![bg center width:500px](../assets/logo_small.png)

---

# Before we start

- Go to the [example repository](https://github.com/CoLRev-Environment/colrev-template)
- Login to GitHub
- Start it in Codespaces
- Slides and cheatsheet are available at XXXX

**TODO : add QR code linking to the slides (directly to this page of the slides)**
**TODO: add the cheatsheet to vscode + rendered version on github/linked (with collapsible showing colrev status)**
**TBD: setup.md in codespaces?**

![bg right:50% width:550px](../assets/start-codespaces.png)

---

# Who are we?

![bg center width:900px](../assets/expertise.png)

TODO : add Guy Paré to HEC Montréal

<!-- 

- Gerit Wagner: short bio

- Julian Prester: short bio

Overview of publications on literature reviews, tools, teaching (phd, bachelor, master), editorial work, ...

Map our journey on the left (started in Regensburg, JP to UNSW, GW to Montreal and Bamberg, JP to University of Sydney)

Illustrate our experience on the right as different "building blocks" with the colrev project on top (e.g., 12 review papers, 4 methods papers, 87 packages, 7 teaching offers, 4 x service as editor/reviewer )

3 methods papers in the senior scholars basket (of 11)
over 50 phd students

colrev projet: setup in 2021 - 3 years under development, 26 versions, 20 contributors, but still a lot to do
 -->

---

# Literature reviews with CoLRev

- An open and extensible platform supporting all steps

    - ``colrev init`` - problem formulation
    - ``colrev retrieve`` - search, prep, dedupe
    - screen (pdf retrieval, pdf preparation)
    - screen
    - data extraction and synthesis

- Based on Git for versioning and collaboration
- Packages for different types of reviews (not just "systematic reviews")

<!-- 
Git-based: the full collaboration model

First slides: what do we mean with colrev/what's our focus?
colrev: literature reviews in collaborative settings

something we discussed earlier, when announcing the workshop (record keeping, put users in a position to report a full standalone paper at all times)

-> Extensible approach, adapting the first steps with parameters, and selecting different packages for the data analysis/extraction/coding/synthesis/RoB
-->

---

# Collaborative literature reviews

Reliability

- open data, open-source code (transparency - using Git to see exactly what was changed) - not the most common approach in the context of LR
- validation of data and code (manual and algorithmic)
- easy undo operations
-> paradigm change: no longer require "blind trust" in algorithms/student assistants

enables / requires

Efficiency

- combining SOTA tools, testing new algorithms
- involve colleagues, student assistants, crowds (variance in quality, availability, cost)
- Reusable: it should be easy to update prior reviews, import samples from review papers published by another author team, or student papers etc. (reuse: one step further than reproducibility)

---

# Tutorial

- small groups
- codespaces: read doc + enter commands
- show the command-line (the colrev init + colrev status)
- GW: prepare worksheet (printed + in codepaces)

---

# Problem formulation

colrev init (with review types, and protocol for notes)

link to docs?

mention paper.md for protocol?

<!-- Note: do not show "a solution" for this part -->

---

# Search

Focus: search

- search: interactively add search (DB + API)
- IEEE (web of science) - publicly accessible download results files
- AIS via api (TEST)

Topic: "microsourcing" 

Note: You may use a topic of your choice, preferrably one that does not return too many results.

If you completed the search, you can continue with `prep` and `dedupe`

<!-- Includes prep and dedupe

dedupe: highlight: single open-source (code  peer reviewed) tool -->

---

# Screen

prescreen

PDF retrieval

Screen (full-texts)

<!-- mention PDF retrieval locally/based on index - 80% -->

---

# Data extraction, analysis, synthesis

- Synthesis with paper.md
- Export as PDF, word (with PRISMA)

---

# Optional items (depending on time left)

- Show search updates (provdie an updated IEEE results file with additional records)?
- backward-search - one or several papers? TEST
- exports to different bib formats / just the sample (TEST!)

<!-- generate profiles?! / structured data -->

---

# Thank you

- How to get in touch, ask for help (literature-review consultation hour/calendly?)
- How to get involved (report bugs, contribute, ...)
- similar to last slide of esmarconf
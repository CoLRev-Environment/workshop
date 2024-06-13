---
marp: true
header: 'Literature review tools workshop at ECIS 2024: CoLRev'
footer: 'Gerit Wagner and Julian Prester'
theme: ub-theme
paginate: true
---

# Three tools to help you navigate and review IS literature

## LitBaskets, PermuSearch & CoLRev

![bg center width:500px](../assets/2024-ECIS-logo.png)

---

# Before we start

- Create a [GitHub account](https://github.com/signup) and log in
- Start the [demo](https://github.com//codespaces/new?hide_repo_select=true&ref=main&repo=767717822)
- The slides are available online:

![width:100px](../assets/2024-ECIS-QR.png)


![bg right:50% width:350px](../assets/start-demo.png)

---

# Who are we?

![bg center width:900px](../assets/expertise.png)


<!-- 
TODO : add Guy Paré to HEC Montréal

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

- Based on Git for data versioning and collaboration
- An open and extensible platform supporting different types of reviews 
- Covers all steps of the process

| Step                      | Operations                |
|----------------------------|--------------------------|
| Problem formulation        | ``colrev init``          |
| Metadata retrieval         | ``colrev search``, ``colrev load``, ``colrev prep``, ``colrev dedupe``        |
| Metadata prescreen         | ``colrev prescreen``     |
| PDF retrieval              | ``colrev pdfs``          |
| PDF screen                 | ``colrev screen``        |
| Data extraction and synthesis | ``colrev data``       |


<!-- 
Git-based: the full collaboration model

First slides: what do we mean with colrev/what's our focus?
colrev: literature reviews in collaborative settings

something we discussed earlier, when announcing the workshop (record keeping, put users in a position to report a full standalone paper at all times)

-> Extensible approach, adapting the first steps with parameters, and selecting different packages for the data analysis/extraction/coding/synthesis/RoB
-->

---

# The potential synergies between reliability and efficiency in collaborative literature reviews

Reliability

- Transparency and openness of data, and open-source code
- Validation of data and code
- Undo operations should be easy

<!--
data: manual and algorithmic
 (transparency - using Git to see exactly what was changed) - not the most common approach in the context of LR
: paradigm change: no longer require "blind trust" in algorithms/student assistants

 enables / requires -->

Efficiency

- Tool testing and innovating
- Team expansion, involving colleagues, student assistants, and crowds (varying performance, availability, and cost)
- Data reuse, e.g., updating prior reviews, importing samples from other review papers, or their PDFs

<!--
 new algorithms and SOTA tools
(reuse: one step further than reproducibility) 
or student papers etc.
-->

---

# The CoLRev tutorial

- Form small groups (2-3 people)
- Start codespaces, read the worksheet and enter the commands
- Consult with the [documentation](https://colrev.readthedocs.io/en/latest/) when necessary

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
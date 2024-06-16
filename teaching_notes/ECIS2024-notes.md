- [ ] GW: check whether commands work (pdf-get, IEEE, backward search)
- [ ] Release (after 0.12.2) to make fixes in AIS available via pypi
- [ ] Add the cheatsheet to vscode + rendered version on github/linked (with collapsible showing colrev status)- add cheatsheet to setup.md in codespaces?
- GW: prepare worksheet (codepaces)

- AIS: 4 results with title/abstract/... match of microsourcing. The 25 results in the AIS library include cases where microsourcing does not match at all?!

## Session

Time (45-50 minutes):

- Intro slides (including init): 10 min (max)
- 3 Tasks: 3x(9+2) = 33
- Last slide / questions: 3 min

Notes:

- When people enter the room: assign badges (depending on experience) and match people with high and low experience to work together
- To paste commands, you may need to press `ctrl+shift+c`
- show the command-line (the colrev init + colrev status)
- Use full commands (colrev search --add instead of -a)
- Remember: "git reset --hard ..." is not available in the git-graph plugin (must be done via the cli)


## Introductory slides

Notes
- Thank Blair for organizing it, appreciate the other tools

Our background
- GW/JP: shared an office at the University of Regensburg as student assistants. JP: UNSW/Uni Sydney, GW: HEC, Uni Bamberg
- We invest a lot of time and efforts to stay up-to-date with the literature review discourse. This is important to design good literature review tools. For instance, we have received the JIT best paper award for our work on Artificial Intelligence and the Conduct of Literature Reviews.
- What distinguishes good literature review tools?
    - you should be confident that the data is handled carefully: for every change, there should be a specific version. If you have coauthors, or student contributors, or if you use new algorithms, or artificial intelligence, you need to see what has changed, and it should be very easy to undo those changes. Today, CoLRev is the only environment in which that is possible. (in other tools, you either go for blind trust, you make a copy every few hours, and you don't let anyone change the data - no team, no algorithms)
    - you want to publish your review in a format that is acceptable at top journals. So, you need rigor, but you also need to distinguish the specific goals and the type of the review. If you use tools that assume everything is a systematic review, or we just use Webster and Watson, it will be noted when you submit the paper. We send a lot of papers back to the authors at ICIS and CAIS for those reasons. There are over 40 different review types and the tools should produce outcomes that are consistent with your review type.

- Powerful research software does not start with a shiny interface. We draw our inspiration from the tidyverse in R, machine learning libraries, or the Git project. It is a deliberate decision to focus on programmatic interfaces and command line tools. (better for reproducibility and innovation) 
- disclaimer: colrev is still under development, we "dogfood our product" (we use it for all our literature review projects)

Literature reviews with CoLRev
- ...


<!-- - TBD: interactively? ask participants who is working on a review project/plans to do so? -->

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

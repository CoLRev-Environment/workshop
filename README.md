# CoLRev workshop

TODOs

- [ ] JP: cheatsheet
- [ ] GW: check whether commands work (pdf-get, IEEE, backward search)
- [ ] Release (after 0.12.2) to make fixes in AIS available via pypi
- [ ] Add the cheatsheet to vscode + rendered version on github/linked (with collapsible showing colrev status)- add cheatsheet to setup.md in codespaces?
- GW: prepare worksheet (printed + in codepaces)


Notes
- thank Blair for organizing it, appreciate the other tools
- We invest a lot of time and efforts to stay up-to-date with the literature review discourse. This is important to design good literature review tools. For instance, we have received the JIT best paper award for our work on Artificial Intelligence and the Conduct of Literature Reviews.
- what distinguishes good literature review tools?
    - you should be confident that the data is handled carefully: for every change, there should be a specific version. If you have coauthors, or student contributors, or if you use new algorithms, or artificial intelligence, you need to see what has changed, and it should be very easy to undo those changes. Today, CoLRev is the only environment in which that is possible. (in other tools, you either go for blind trust, you make a copy every few hours, and you don't let anyone change the data - no team, no algorithms)
    - you want to publish your review in a format that is acceptable at top journals. So, you need rigor, but you also need to distinguish the specific goals and the type of the review. If you use tools that assume everything is a systematic review, or we just use Webster and Watson, it will be noted when you submit the paper. We send a lot of papers back to the authors at ICIS and CAIS for those reasons. There are over 40 different review types and the tools should produce outcomes that are consistent with your review type.
    - Powerful research software does not start with a shiny interface. We draw our inspiration from the tidyverse in R, machine learning libraries, or the Git project. It is a deliberate decision to focus on programmatic interfaces and command line tools. (better for reproducibility and innovation) 
disclaimer: colrev is still under development, we "dogfood our product" (we use it for all our literature review projects)


## Session

Time (45-50 minutes):

- Intro slides (including init): 10 min (max)
- 3 Tasks: 3x(9+2) = 33
- Last slide / questions: 3 min

Notes:

- When people enter the room: assign badges (depending on experience) and match people with high and low experience to work together
- show the command-line (the colrev init + colrev status)
- Use full commands (colrev search --add instead of -a)
- Remember: "git reset --hard ..." is not available in the git-graph plugin (must be done via the cli)

## Materials

```
make slides
```

Creates slides in `output` directory.


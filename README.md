# The Geometry of Evidence — The Living Minard

**An interactive visual essay on Charles Joseph Minard's 1869 map**  
**Interactive publication:** Christopher Hayes, CDAIO  
**Original historical graphic:** Charles Joseph Minard (1869)

[**Launch the interactive essay on GitHub Pages**](https://chrisdhayes.github.io/The_Geometry_Of_Evidence_Living_Minard/)

> **Publication note:** The link becomes active after GitHub Pages has been configured and the deployment succeeds.

## About the project

What makes a visualization persuasive—and what evidence does it actually justify? *The Geometry of Evidence* is a five-part visual essay that lets readers examine the original 1869 Minard plate, learn how its graphical encodings work, trace the published historical observations, and challenge interpretations that go beyond the evidence.

The reading journey includes an archival visual comparison; four close-reading challenges; a guided interpretation; an interactive ribbon transformation; and an investigation lab. An evidence-and-methods section provides observation tables and an offline JSON export.

## Open and publish

**This repository can be published as a single-file static site.** Its `index.html` is the self-contained V12 edition, with code, visual assets and observations embedded. No package installation, build process, server-side runtime, CDN, or API key is needed. Download the HTML file and open it locally to use the interactive essay offline; external scholarship links require internet access.

To publish: in repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, and save. The expected address is `https://chrisdhayes.github.io/The_Geometry_Of_Evidence_Living_Minard/` (subject to the repository's exact spelling and Pages configuration).

## Evidence and interpretive safeguards

- Historical rows derive from the **HistData / Rdatasets Minard transcription**: 51 troop observations, 20 city records and nine temperature observations.
- The 51 troop records provide position, formation, direction and number of men present, **not a daily troop-count series**. Eight of the nine temperature records include explicit dates.
- The 422,000 combined opening number refers to **three separate formations** (340,000 + 60,000 + 22,000), not one continuous ribbon.
- A difference in men present is **not itself a count of deaths**, nor sufficient to assign losses to winter or any specific cause.
- The digital overlays and image-registration control points are *interpretive reconstructions*. They should not be mistaken for an independently verified, pixel-exact transcription of the 1869 engraving.

The full standalone publication contains its own evidence contract, source-linked explanations, and accessible data tables.

## Original sources and credits

- Charles Joseph Minard, *Carte figurative des pertes successives en hommes de l'Armée Française dans la campagne de Russie*, 1869. Historical image is public-domain material.
- [HistData Minard transcription — Rdatasets](https://vincentarelbundock.github.io/Rdatasets/doc/HistData/Minard.temp.html) (data and documentation).
- Historical context and additional references are identified in the essay itself.

**Authorship:** Christopher Hayes, CDAIO (interactive visual essay, analysis, text, interfaces and visual reconstructions). Original graphic: Charles Joseph Minard (1869). Data transcription: HistData and its credited sources.

## Quality and limits

The V12 release candidate was reviewed locally for desktop/mobile layout and cross-exhibit behaviour. **A live GitHub Pages deployment has not yet been verified** as of this README's preparation. Independent archival registration; full WCAG/assistive-technology validation; Safari, Firefox and physical-device field testing; and user-comprehension studies remain outside the completed testing scope.

## Licensing

The original 1869 Minard graphic is public domain. The modern interactive project has **not been assigned an open-source license** here. Public visibility on GitHub does not automatically grant permission to reuse the modern project. Licensing can be specified separately if the author chooses.

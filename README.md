# The Geometry of Evidence — The Living Minard

**An interactive visual essay about what evidence shows, what visualizations imply, and what readers can responsibly conclude.**

**Interactive essay and commentary:** Christopher Hayes, CDAIO  
**Original statistical graphic:** Charles Joseph Minard (1869)  
**Interactive edition:** V12 release candidate · 2 November 2026

[**Explore the interactive visual essay**](https://chrisdhayes.github.io/The_Geometry_Of_Evidence_Living_Minard/)

> **Deployment status:** This is the expected GitHub Pages URL for the repository name shown. Verify that Pages has deployed successfully before publicly sharing the link or the companion article.

## Companion article

**A Chart Can Be Right—and Still Make Us Wrong** — a research-supported essay about Minard's explicit representational assumptions, the distinction between historical evidence and causal explanation, and what this means for contemporary analytics and generative AI.

The article accompanies—not replaces—the interactive publication. It develops the argument; this repository provides opportunities to inspect the evidence behind that argument.

**Substack permalink:** *Add the live Substack URL here after publication.* (Do not insert an unverified or placeholder hyperlink.)

### Direct links to the experience

Use these links in essays, presentations, teaching material and discussions to direct readers to a relevant part of the publication:

| Area | What readers can do | Deep link |
| --- | --- | --- |
| **Original** | Inspect the historical print and compare reconstructions | [Open original](https://chrisdhayes.github.io/The_Geometry_Of_Evidence_Living_Minard/#archive) |
| **Read** | Work through four close-reading challenges | [Open close-reading lab](https://chrisdhayes.github.io/The_Geometry_Of_Evidence_Living_Minard/#reading-studio) |
| **Understand** | Follow five movements of the visual argument | [Open guided story](https://chrisdhayes.github.io/The_Geometry_Of_Evidence_Living_Minard/#story) |
| **Transform** | Unfold geographic ribbons into source-linked observations | [Open transformation](https://chrisdhayes.github.io/The_Geometry_Of_Evidence_Living_Minard/#unfold) |
| **Investigate** | Test quantities, encodings, temperature and causal claims | [Open evidence lab](https://chrisdhayes.github.io/The_Geometry_Of_Evidence_Living_Minard/#observe) |
| **Evidence & methods** | Review source distinctions, limitations and tabular data | [Open methods](https://chrisdhayes.github.io/The_Geometry_Of_Evidence_Living_Minard/#methods) |
| **References** | Consult underlying historical and academic sources | [Open sources](https://chrisdhayes.github.io/The_Geometry_Of_Evidence_Living_Minard/#sources) |

The links point to **existing HTML IDs** in the V12 publication. They do not select individual troop rows or save every interface control state; implementing shareable analytical state would be a separate future enhancement.

## About the experience

The five-act interactive publication comprises an archival visual comparison; four close-reading challenges; guided interpretation; an interactive ribbon transformation; and an investigation laboratory. An evidence-and-methods section documents source distinctions, interpretive safeguards, 51 troop observations, 20 cities and nine temperature records, along with an offline JSON export.

This research asks: *How can information design help people distinguish a faithful representation of data from a conclusion the data does not establish?*

## How to publish and use

For **single-file deployment**, publish the self-contained V12 HTML as repository-root `index.html`. That edition embeds styles, scripts, images and data; it requires no build tool, runtime server, CDN or API key. GitHub Pages: **Settings → Pages → Deploy from a branch → main → /(root)**.

For **modular deployment**, use the **complete V12 release folder**—not only the individually uploaded CSS/JS files. Retain relative `assets/`, `data/` and `docs/` references and all source files. Do not mix the modular `index.html` with the self-contained single-file edition without planning which is authoritative.

Offline use: download the self-contained HTML and open it in a modern browser. Scholarly links leave the site and require connectivity.

## Evidence and interpretive safeguards

- Source rows derive from the **HistData transcription**: 51 troop observations, 20 cities and nine temperature entries. The troop records describe positions, groups, directions and men present, **not a daily census**; eight of nine temperature entries have explicit dates.
- **422,000** is the combined opening estimate across three separately represented formations (340,000 + 60,000 + 22,000)—not one uninterrupted ribbon.
- Changes in estimated **men present** do not, on their own, establish the number of deaths or apportion their causes.
- Animation between troop records is **visual interpolation**. It should not be mistaken for newly measured daily observations.
- The archival image is an original historical graphic; the digital SVG overlays and hand-selected alignment landmarks are **provisional interpretive reconstructions**, not an independently verified pixel-exact registration.
- This V12 edition has not yet completed formal WCAG/assistive-technology review, Safari/Firefox and physical-device field testing, or a real-user comprehension study.

## Primary research and references

1. Charles Joseph Minard (1869), *Carte figurative des pertes successives ...*, [BnF catalogue record](https://catalogue.bnf.fr/ark:/12148/cb40650878p).
2. Michael Friendly (2002), [*Visions and Re-Visions of Charles Joseph Minard*](https://doi.org/10.3102/10769986027001031).
3. Menno-Jan Kraak (2021), [*The best map ever?*](https://doi.org/10.1080/23729333.2021.1909404).
4. [HistData / Minard data documentation](https://friendly.github.io/HistData/reference/Minard.html).
5. Cindy Xiong et al. (2020), [*Illusion of Causality in Visualized Data*](https://doi.org/10.1109/TVCG.2019.2934399).
6. Alex Kale, Yifan Wu & Jessica Hullman (2022), [*Causal Support*](https://doi.org/10.1109/TVCG.2021.3114824).
7. Jessica Hullman (2020), [*Why Authors Don't Visualize Uncertainty*](https://doi.org/10.1109/TVCG.2019.2934287).
8. NIST (2024), [*Generative AI Profile*, NIST AI 600-1](https://doi.org/10.6028/NIST.AI.600-1).

For the full narrative, see the companion Substack article; for observation-level verification and reconstruction limits, use **Evidence & methods** inside the interactive experience.

## Attribution, quality and reuse

**Modern interactive work:** Christopher Hayes, CDAIO (interpretation, writing, interface and graphical reconstructions). **Original historical graphic:** Charles Joseph Minard (1869), public domain. **Data transcription:** HistData and credited historical sources.

This is a publication and research project, not a peer-reviewed historical correction to Minard. V12 had desktop/mobile automated regression tests locally; a live remote deployment, independent archival registration and formal accessibility certification were **not** verified in that process.

**License:** The original 1869 graphic is public domain. No open-source license has been selected for the modern application or article. Public access is not itself a licence to republish or modify the modern source.

# Task: Add 2025–2026 papers to tomemery.eu

Add the 7 papers below to the site: https://tomemery.eu/ — both the **Publications** section and the **homepage summaries** ("Recent Work" — the featured list with a short 1–2 sentence description per entry, currently showing entries from Dec 2023–Dec 2024).

## How the site is currently structured (from the live pages, not the repo — verify against the actual source)

- Nav: Projects, Publications, Contact
- Homepage has a "Recent Work" section: ~6 featured entries, each with authors (linked), month/year, linked title, a 1–2 sentence description, and a PDF/external link.
- A "Selected Publications" section lists more entries (title, authors, PDF/DOI/citation links).
- This looks like a Hugo academic-CV-style site (URLs like `/project/ercstg/` follow Hugo's `content/project/<slug>/` pattern). If so, publications likely live as individual entries under something like `content/publication/<slug>/index.md` with frontmatter (title, authors, date, publication venue, DOI, abstract/summary, links), and the homepage "Recent Work" list is probably just the N most recent publications pulled automatically, sorted by date — in which case adding these to the publications collection with correct `date` fields may be all that's needed for the homepage to update itself. **Confirm this by inspecting the actual repo before editing** — don't guess further than this.
- Match the existing format/frontmatter fields exactly (look at an existing entry like the COVID-19 school/family networks paper or the "potential of benchmark challenges" paper as a template).
- For the short homepage description of each entry, write 1–2 plain sentences in the same style as the existing "Recent Work" blurbs (concise, non-technical framing of the finding) — draft these from the abstracts below.
- **Every existing publication entry has a featured image** (`featured.png` or similar, e.g. `content/publication/covidspread/featured.png`) — it's shown as a large hero image on the individual publication page (`/publication/<slug>/`) and also inline in the Publications listing above each entry's title/abstract. This is not optional/decorative-only — every entry checked has one, and it's normally a figure or diagram lifted straight from the paper (a results plot, a schematic of the method, a network diagram), not a generic stock image or the site's logo. **Each of the 7 new entries needs one too** — see the "Featured images needed" section near the end of this file.

## The 7 papers to add

Ordered newest-first by best available date estimate. Insert them into the publications list/homepage in the correct chronological position among existing entries.

---

### 1. Embeddings of Nation-Level Social Networks
- **Authors:** Tanzir Pial, Flavio Hafner, Dakota Handzlik, Enamul Hassan, Lucas Sage, Ana Macanovic, Tom Emery, Arnout van de Rijt, Steven Skiena
- **Venue:** arXiv preprint
- **arXiv ID:** 2603.29059 (→ March 2026)
- **Link:** https://arxiv.org/abs/2603.29059
- **Google Scholar:** https://scholar.google.co.uk/citations?view_op=view_citation&hl=en&user=LvKf9cMAAAAJ&sortby=pubdate&citation_for_view=LvKf9cMAAAAJ:Mojj43d5GZwC
- **Abstract:** Population-scale social networks are now emerging from administrative records in countries including the Netherlands and Denmark, though these datasets present technical challenges when working with large, multiplex, and time-dependent structures. This paper reports on producing dynamic node embeddings for the Dutch population network, with three contributions: (1) a layer-sensitive random walk strategy improving on traditional flattening approaches for multiplex networks; (2) a temporal alignment method that projects annual networks into a unified embedding space without information leakage from future years; and (3) use of Fibonacci spirals and embedding whitening for balanced node partitioning. The techniques are validated across 13 downstream predictive tasks, showing effectiveness for income prediction, demographic events, and survey responses linked to administrative and survey data.

---

### 2. How do Modes of Data Collection Affect the Measurement of Demographic Key Indicators? Findings from a Three-Country Experiment Using the Generations and Gender Survey
- **Authors:** D. Lück, A. Schumann, T. Emery, P. Lugtig, M. Bujard, R. Naderi, V. Toepoel, S. Cabaço
- **Venue:** Likely *European Journal of Population* (DOI prefix 10.1007/s10680-...) — confirm venue name before publishing
- **Year:** 2026
- **DOI:** https://doi.org/10.1007/s10680-026-09777-7
- **Google Scholar:** https://scholar.google.co.uk/citations?view_op=view_citation&hl=en&user=LvKf9cMAAAAJ&sortby=pubdate&citation_for_view=LvKf9cMAAAAJ:5awf1xo2G04C
- **Abstract:** Survey methodology has shifted from face-to-face interviews (CAPI) to web-based approaches (CAWI) due to rising costs and pandemic-era restrictions. This study analyzes how that transition affects demographic measurement, using Generations and Gender Survey data from Germany, Croatia, and Portugal. It identifies distinct selection effects — underrepresentation of less-educated respondents in web surveys, and urban underrepresentation in in-person modes — and shows measurement effects vary by indicator and country: CAWI shows less social-desirability bias on sensitive topics, while in-person interviews show reduced satisficing bias; loop questions with high respondent burden are particularly challenging. The authors recommend using weights, controlling for mode in analyses, and acknowledging mode differences when interpreting results to preserve comparability across datasets.

---

### 3. Mapping spatial colleague connectivity patterns from individual-level registry data to inform regional pandemic interventions
- **Authors:** PingPing Song, Sake J. de Vlas, Tom Emery, Luc E. Coffeng
- **Venue:** PLOS Computational Biology
- **Year:** 2026, Volume 22, Issue 8, Article e1014721
- **DOI:** https://doi.org/10.1371/journal.pcbi.1014721
- **Preprint (medRxiv):** https://doi.org/10.64898/2026.02.19.26346499
- **Google Scholar:** https://scholar.google.co.uk/citations?view_op=view_citation&hl=en&user=LvKf9cMAAAAJ&sortby=pubdate&citation_for_view=LvKf9cMAAAAJ:t6usbXjVLHcC
- **Abstract:** This paper addresses a gap in infectious disease modeling by quantifying geographical connectivity from employment registry data covering over 8 million Dutch workers, producing colleague-connectedness metrics indexed by municipality triplets (two residential municipalities, one workplace municipality). Using SARS-CoV-2 Omicron spread as a test case, a two-fold increase in within-province connections is associated with a 3.7-day earlier onset, and between-province connectivity with a 2.5-day earlier onset. Regional lockdown scenarios show heterogeneous impacts — locking down Zeeland would remove 2.6% of national colleague links, whereas Amsterdam alone would remove 10.0%. The authors argue this fine-grained spatial connectivity data can serve as spatial mixing matrices in future transmission models, enabling more regionally targeted pandemic policy.

---

### 4. Family networks and childcare choices: A predictive machine learning approach
- **Authors:** Nicolás Soler, Tom Emery, Agnieszka Kanas
- **Venue:** Sociological Science
- **Year:** 2026, Volume 13, pages 589–613
- **DOI:** https://doi.org/10.15195/v13.a23
- **PDF:** https://sociologicalscience.com/download/volume-13/june/SocSci_v13_589to613.pdf
- **Google Scholar:** https://scholar.google.co.uk/citations?view_op=view_citation&hl=en&user=LvKf9cMAAAAJ&sortby=pubdate&citation_for_view=LvKf9cMAAAAJ:HE397vMXCloC
- **Abstract:** How first-time parents arrange childcare has critical implications for their careers and their child's development. Prior research treats family care availability as an additive function of a small set of parental and grandparental characteristics, but research on family networks suggests it is instead a non-linear, non-additive function of larger family networks. Using a machine learning framework and register-based family network data, the authors compare the predictive power of these two perspectives. Accounting for how great-grandparents, aunts, uncles, and cousins shape care availability — and modeling their influence with more flexible models — yields small but significant improvements in predictive accuracy, particularly for more disadvantaged parents. Predictions are driven mainly by parents' and grandparents' socioeconomic characteristics, but cousins' age and daycare use are important, understudied predictors, alongside parents' self-employment, healthcare spending, and timing of daycare uptake.

---

### 5. Decentralization and Re-familialization in Informal Care: Adaptability and Inequalities in Social Care Policies in the Netherlands
- **Authors:** Gita Huijgen, Tom Emery, Pearl A. Dykstra, Mirjam de Klerk
- **Venue:** Social Politics: International Studies in Gender, State & Society (Oxford University Press)
- **Year:** 2026 (advance article), article no. jxag038
- **DOI:** https://doi.org/10.1093/sp/jxag038
- **Link:** https://academic.oup.com/sp/advance-article/doi/10.1093/sp/jxag038/8738448
- **Google Scholar:** https://scholar.google.co.uk/citations?view_op=view_citation&hl=en&user=LvKf9cMAAAAJ&sortby=pubdate&citation_for_view=LvKf9cMAAAAJ:9vf0nzSNQJEC
- **Abstract:** This paper examines how Dutch municipalities have implemented decentralized, re-familialized social care policies intended to reduce public spending. Using survey data from 242 municipalities, it asks how much municipal variation exists in activating and supporting informal care, whether local demographic, cultural, political, and financial factors explain differences in implementation, and whether familialism correlates with lower formal-care use or expenditure. The findings show only modest municipal variation in familialism approaches, weakly linked to local context, and — contrary to policy expectations — lower formal care utilization in municipalities with greater care needs. The authors conclude that decentralization does not deliver on its promise of adaptability and equal outcomes when legal and budgetary constraints limit local discretion, and that re-familialization has not clearly reduced reliance on public services — suggesting the reforms may redistribute costs to families rather than achieve sustainable system change.

---

### 6. The Critical Juncture of Childbirth: Periodic Turbulence in the Employment Trajectories of Mothers in Europe
- **Authors:** Tom Emery, Alžběta Bartova, Maximilian Reichert
- **Venue:** Working paper / SocArXiv preprint (confirm if since published in a journal)
- **Year:** 2025
- **DOI:** https://doi.org/10.31235/osf.io/y4f3j
- **Related summary:** https://socialpolicyworldwide.org/post/turbulence_in_employment_trajectories__40
- **Google Scholar:** https://scholar.google.co.uk/citations?view_op=view_citation&hl=en&user=LvKf9cMAAAAJ&sortby=pubdate&citation_for_view=LvKf9cMAAAAJ:WqliGbK-hY8C
- **Abstract (partial — confirm full abstract from the OSF/SocArXiv page, which is JS-rendered and couldn't be scraped automatically):** The transition to parenthood is a main driver of gender inequalities in employment. Using EU-SILC data, this paper examines employment patterns around childbirth across European countries, characterizing the disruption as periodic turbulence in mothers' employment trajectories around this critical juncture.

---

### 7. Inequalities in early childcare strategies: Evidence from Dutch administrative data
- **Google Scholar:** https://scholar.google.co.uk/citations?view_op=view_citation&hl=en&user=LvKf9cMAAAAJ&sortby=pubdate&citation_for_view=LvKf9cMAAAAJ:WA5NYHcadZ8C
- **⚠️ UNRESOLVED — could not find this paper anywhere except the Google Scholar citation link.** Google Scholar's citation pages are blocked to automated fetching (robots.txt), and no other search turned up authors, venue, year, DOI, or an abstract. This is very likely tied to Tom's ERC Starting Grant "Childcare Strategies" project (https://tomemery.eu/project/ercstg/), so probable co-authors are among Agnieszka Kanas, Nicolás Soler, Gita Huijgen — but **do not guess and publish this**.
- **Action needed before publishing this entry:** open the Google Scholar citation link above (in a logged-in browser) and copy the authors, venue/journal, year, and abstract/description shown there, then fill in this section and proceed the same way as the other 6.

---

## Featured images needed

Each of the 7 entries needs a `featured.png` (or `.jpg`) in its publication folder — matching how every existing entry has one (confirmed by viewing the live site: e.g. `/publication/covidspread/` shows a school-transition network diagram credited to a co-author; the mode-effects-style entries show results plots; the benchmark-challenges paper shows a flowchart). Source one figure per paper, in priority order:

1. **Pull a figure straight from the paper** — the published PDF, the preprint PDF, or (for the arXiv paper) the HTML version. Good candidates: a results plot, a map, a network/schematic diagram — something that reads well as a standalone thumbnail, the way the existing entries do. Save it as `featured.png` in that publication's content folder.
2. If a paper has no single figure that stands alone well (e.g. it's mostly regression tables), ask Tom which figure he'd like used, or whether to generate a simple schematic instead.
3. Do not substitute a generic/stock image, the site logo, or an AI-generated illustration without checking with Tom first — every existing entry uses a real figure from the paper.

Papers and where to pull a candidate figure from:

- **#1 Embeddings of Nation-Level Social Networks** — arXiv HTML version (https://arxiv.org/html/2603.29059) or PDF (https://arxiv.org/pdf/2603.29059v1); likely candidate: an embedding visualization or the layer-sensitive random-walk schematic.
- **#2 Modes of Data Collection...** — DOI https://doi.org/10.1007/s10680-026-09777-7; likely candidate: a mode-comparison plot (CAWI vs CAPI/F2F), similar in style to the existing "Survey Mode" entry's chart.
- **#3 Mapping spatial colleague connectivity...** — PLOS Comp Biol (https://doi.org/10.1371/journal.pcbi.1014721) or medRxiv preprint (https://doi.org/10.64898/2026.02.19.26346499); likely candidate: the municipality-connectivity map or the Zeeland/Amsterdam lockdown-scenario figure.
- **#4 Family networks and childcare choices...** — PDF at https://sociologicalscience.com/download/volume-13/june/SocSci_v13_589to613.pdf; likely candidate: a feature-importance plot or the family-network schematic.
- **#5 Decentralization and Re-familialization...** — https://academic.oup.com/sp/advance-article/doi/10.1093/sp/jxag038/8738448; likely candidate: a municipal-variation map or chart of familialism vs. care utilization.
- **#6 The Critical Juncture of Childbirth...** — OSF/SocArXiv preprint (https://doi.org/10.31235/osf.io/y4f3j), page is JS-rendered so open it directly rather than scraping; likely candidate: an employment-trajectory plot around childbirth.
- **#7 Inequalities in early childcare strategies...** — no source located yet (see unresolved note above); get the figure once the paper itself is identified via the Google Scholar link.

## What to do

1. Locate the repo for tomemery.eu (check for a Hugo/Wowchemy-style `content/publication/` directory, or whatever the actual publication data structure is).
2. For each of the 7 papers above, create a new publication entry following the exact format/frontmatter of an existing recent entry (e.g. the Dec 2024 COVID-19 school/family networks paper), filling in title, authors (with links to existing author pages where those people already have entries, e.g. Tom Emery himself), date, venue, DOI/links, and abstract.
3. Write a short 1–2 sentence homepage-style summary for each (see abstracts above) in the same tone as the existing "Recent Work" blurbs, and confirm whether the homepage list needs manual editing or updates automatically from the publications collection.
4. Source and add a `featured.png` figure for each entry per the "Featured images needed" section above — don't leave entries without one, since every existing publication has one.
5. Resolve paper #7 by getting its details manually from Google Scholar (see above) before adding it — don't publish placeholder/guessed data.
6. Build/preview the site locally to confirm the new entries (including their featured images) render correctly, then commit.

# ?? Desk-Reject Pre-Flight Checklist: 30 Editorial Quality Gates

> **Standard Editorial Assessment Protocol for High-Impact Journals (IEEE, Elsevier, Springer Nature, Wiley, MDPI)**  
> *Targeted at preventing instant desk-rejections, formatting triage bounces, and Editor-in-Chief administrative dismissals.*

---

## ?? Executive Summary
Over **40% to 60% of submitted manuscripts** to Q1 journals are rejected by the Editor-in-Chief (EiC) or handling editor *before* being assigned to peer reviewers. The vast majority of these desk rejections are not due to lack of novel ideas, but due to **structural non-compliance, missing baseline comparisons, poorly formatted equations/figures, or outdated literature reviews**.

Use this comprehensive checklist before clicking **Submit** on any journal portal (Editorial Manager, ScholarOne, Elsevier Evise, etc.).

---

## ?? Section 1: Title, Abstract & Scope Fit

- [ ] **1. Exact Scope Congruence:** Does the paper directly address at least two focus areas listed in the journal's official "Aims & Scope"? *(If your paper is pure application and the journal requires theoretical novelty, it will be desk-rejected immediately).*
- [ ] **2. Information-Dense Title:** Is the title concise (< 15 words) and descriptive, explicitly stating the core methodology and problem domain without sensational marketing adjectives (*"revolutionary"*, *"breakthrough"*, *"cutting-edge"*)?
- [ ] **3. Structured Abstract Structure:** Does the abstract clearly cover the 5 essential pillars:
  1. *Context & Problem Statement* (1?2 sentences)
  2. *Unaddressed Research Gap* (1 sentence)
  3. *Proposed Methodology & Technical Mechanism* (2?3 sentences)
  4. *Quantitative Validation Metrics* (e.g., exact % improvement, latency reduction, F1-score)
  5. *Practical Significance / Broad Impact* (1 sentence)
- [ ] **4. Abstract Length Bounds:** Does the word count strictly comply with the journal guide (typically 150?250 words)?
- [ ] **5. Author-Selected Keywords:** Are there 4 to 6 standardized domain terms from recognized thesauri (e.g., IEEE Taxonomy, MeSH, ACM Computing Classification System), avoiding overly broad single words like *"computer"*, *"memory"*, or *"system"*?

---

## ?? Section 2: Introduction, Literature Review & Research Gap

- [ ] **6. The "So What?" Articulation:** Does the first page answer why this problem is critical *now* and why existing solutions are insufficient?
- [ ] **7. Recency of Cited Literature:** Are at least **40%?50% of the cited references from the last 2 to 3 years** (2023?2026)? *(Citing only pre-2020 literature signals to the editor that your team is out of touch with the current state of the art).*
- [ ] **8. Synthetic vs. Sequential Literature Review:** Does the literature review synthesize related works thematically and comparatively, rather than listing authors one by one (*"Author A did this. Author B did that"* without critical comparison)?
- [ ] **9. Explicit Gap Identification:** Is there a dedicated paragraph stating: *"Despite these advances, existing approaches suffer from three primary limitations: (1)..., (2)..., and (3)..."*?
- [ ] **10. Bulleted List of Novel Contributions:** Does Section 1 end with an explicit bulleted list of 3 or 4 clear, verifiable contributions, differentiating technical mechanism from empirical validation?

---

## ?? Section 3: Methodology & Mathematical Rigor

- [ ] **11. Reproducibility Baseline:** Are all experimental parameters, hyperparameters, hardware configurations, and software library versions explicitly detailed in a dedicated table?
- [ ] **12. Native Equation Typesetting (OMML / MathType):** Are all equations formatted as editable native equations (Word OMML or MathType), rather than blurry rasterized PNG/JPEG images pasted into the document?
- [ ] **13. Grammatical Equation Punctuation:** Are all displayed equations treated as grammatical elements of the sentence, followed by correct commas or periods?
- [ ] **14. Variable Definition Consistency:** Are all mathematical symbols defined upon their first appearance in the text? Does the notation remain consistent (e.g., bold for vectors/matrices, italics for scalar variables)?
- [ ] **15. Equation Numbering:** Are all display equations sequentially numbered on the right-hand margin with parenthesis `(1)`, `(2)`, etc.?

---

## ?? Section 4: Figures, Tables & Visual Quality

- [ ] **16. Print-Ready Resolution (300+ DPI):** Are all raster figures (PNG/TIFF) at least 300 DPI at final print width? Are vector formats (SVG, PDF, EPS) used for plots, architectures, and diagrams?
- [ ] **17. Legibility at Single-Column Width:** If the target journal is two-column (e.g., IEEE, Elsevier, Nature), are text labels and axis ticks inside figures readable when shrunk to 8.5 cm (3.3 inches) width?
- [ ] **18. Self-Contained Captions:** Can an editor or reviewer understand the figure/table and its main takeaway solely by reading the caption without hunting through the body text?
- [ ] **19. Direct Body Cross-Referencing:** Is every figure and table explicitly referenced in the body text (e.g., *"As illustrated in Fig. 3..."*) prior to its visual placement?
- [ ] **20. Three-Line Table Standard (Booktabs):** Are tables formatted with clean horizontal lines (top rule, mid rule, bottom rule) and zero vertical grid lines?

---

## ?? Section 5: Experimental Evaluation & Benchmark Validation

- [ ] **21. Strong, Contemporary Baselines:** Are you benchmarking against state-of-the-art methods published in Q1 venues within the last 18?36 months, rather than comparing solely against weak, decade-old baselines?
- [ ] **22. Statistical Rigor & Variance:** Do all reported quantitative metrics include standard deviations, error bars, or 95% confidence intervals over multiple independent runs ($n \ge 5$)?
- [ ] **23. Honest Limitations Section:** Is there a dedicated subsection explicitly detailing the operational constraints, failure modes, and boundary limitations of your proposed method? *(Papers claiming 100% flawless results without limitation are universally distrusted by reviewers).*
- [ ] **24. Fair Ablation Studies:** Is there an ablation study isolating the contribution of each proposed module, parameter, or loss function?

---

## ?? Section 6: Citations, References & Compliance

- [ ] **25. Accurate Citation Style:** Does the reference list follow the exact target journal style (IEEE numeric `[1]`, APA author-date, Harvard, or Nature superscripts)?
- [ ] **26. Active DOIs:** Does every single journal and conference reference entry include a valid, active DOI link (`https://doi.org/10...`)?
- [ ] **27. Zero Self-Citation Stacking:** Does the author team's self-citation rate remain strictly under 15% of total citations?
- [ ] **28. Mandatory Ethical Declarations:** Are all required statements present at the end of the manuscript:
  - *Conflict of Interest / Competing Interests Statement*
  - *Data & Code Availability Statement* (with working repository / Zenodo DOI link)
  - *Funding & Acknowledgments*
  - *CRediT Author Statement* (Conceptualization, Methodology, Software, Validation, etc.)
- [ ] **29. Blind Review Anonymity (if Double-Blind):** Have author names, affiliations, grant numbers, institutional acknowledgments, and repository URLs been completely scrubbed for double-blind venues?
- [ ] **30. Page & Word Count Compliance:** Does the total page count, including references and bios, strictly adhere to the journal maximum?

---

## ? Automate Your Pre-Flight Audit Online

Checking 30 points manually takes hours and still leaves room for human error. 

[![Automate with Reviewer 2 Pre-Flight](https://img.shields.io/badge/Automate_With-Reviewer_2_Pre--Flight-blue?style=for-the-badge&logo=shield)](https://manuscriptos.io/?utm_source=github&utm_medium=lead_magnet&utm_campaign=academic_publishing_toolkit)

Run your manuscript draft through **[ManuscriptOS Reviewer 2 Pre-Flight](https://manuscriptos.io/?utm_source=github&utm_medium=lead_magnet&utm_campaign=academic_publishing_toolkit)** to automatically scan:
* 40+ structural and editorial compliance metrics
* Active Crossref DOI validation and broken link detection
* Reference age distribution and Q1 quartile scoring
* Native equation and typography verification
* Instant actionable recommendations before you submit!
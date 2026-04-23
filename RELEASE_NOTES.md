# The EB-2 NIW Framework — Version 1.0

**Release Date:** April 22, 2026  
**Author:** Wederson Marinho  
**Repository:** https://github.com/imigrascore/eb2-niw-framework

---

## What's Included in v1.0

### Core Framework

**Complete Dhanasar Analysis**
- Full technical breakdown of *Matter of Dhanasar, 26 I&N Dec. 884 (AAO 2016)*
- Integration of January 15, 2025 USCIS Policy Manual update (PA-2025-03)
- Three-prong test with practical adjudication application
- Distinction between EB-2 eligibility threshold and NIW prongs

**EB-2 Eligibility Guidance**
- Advanced Degree Professional pathway (degree requirements, experience thresholds)
- Exceptional Ability pathway (three-of-six USCIS criteria)
- INA Section 203(b)(2) compliance framework

**Proposed Endeavor Construction**
- Four structural failures that trigger RFEs
- Specificity test (the realism test)
- Examples: weak vs. strong across professions
- Field-specific guidance (researchers, clinicians, entrepreneurs)

**RFE Risk Analysis**
- 12 documented risk signals organized by Dhanasar prong
- High-risk, moderate-risk, and low-risk categorization
- Preemption strategies for each signal
- Common adjudication patterns

**Self-Assessment Framework**
- Six-step methodology for evaluating petition strength
- Classification system (Strong, Moderate, Borderline, Weak)
- Decision trees for prong-by-prong evaluation

### Educational Resources

**30+ FAQ**
- Real candidate questions answered
- Technical accuracy with practical context
- Covers eligibility, proposed endeavor, evidence, process, and RFE response

**Guides (HTML + Markdown)**
- Dhanasar Framework (comprehensive technical reference)
- Proposed Endeavor (construction and pitfalls)
- RFE Risk Signals (risk analysis by prong)
- FAQ (Q&A format)

**Templates (HTML + Markdown)**
- Case Strength Framework (self-assessment with print support)
- Evidence Checklist (documentation inventory)

### Documentation

**Citation Standards**
- APA 7th Edition format
- BibTeX for academic reference managers
- Chicago Style for legal citations
- Zenodo DOI support (pending deposit)

**Contributing Guidelines**
- Standards for error reports
- Submission process for improvements
- Clear acceptance/rejection criteria

**Source Attribution**
- Primary legal authorities documented
- References to USCIS Policy Manual, Dhanasar decision, and regulations
- Hyperlinked citations for verification

**License**
- Creative Commons Attribution 4.0 International (CC BY 4.0)
- Free to share, adapt, and build upon with attribution

### Technical Features

**GitHub Pages Integration**
- Live site at https://imigrascore.github.io/eb2-niw-framework/
- Jekyll-based static site generation
- Responsive design optimized for mobile and desktop
- Professional typography (Cormorant Garamond + DM Sans)

**SEO Optimization**
- Schema.org structured data (LearningResource, FAQPage, BreadcrumbList)
- OpenGraph and Twitter Card metadata
- Semantic HTML and accessibility compliance
- Proper canonical URLs

**Version Control**
- Git-based repository structure
- Clear .gitignore for Jekyll projects
- Contributing workflow documented

---

## What This Framework Does NOT Include

- **Legal advice** — This is educational content only
- **Case-specific analysis** — Not applicable to individual situations
- **Approval guarantees** — USCIS adjudication depends on specific evidence
- **Automated processing** — No automated filing, application generation, or decision prediction

---

## Required Reading Before Use

1. **Legal Disclaimer** (in every guide and on main site)
2. **Controlling Legal Authority** (Matter of Dhanasar, 26 I&N Dec. 884; USCIS Policy Manual)
3. **CONTRIBUTING.md** (standards for accuracy if reporting errors)

---

## For GitHub Release Deployment

### File Checklist (Do Not Include)
- ❌ `.git/` directory (Git automatically ignores)
- ❌ `.github/` directory (removed; CI/CD planned for v1.1)
- ❌ `assets/` directory (empty; removed)
- ❌ OS-specific files (.DS_Store, Thumbs.db, etc.) — ignored by .gitignore

### File Checklist (Do Include)
- ✅ All guides (`/guides/*.md` and `*.html`)
- ✅ All templates (`/templates/*.md` and `*.html`)
- ✅ Main site (`index.html`)
- ✅ Layout template (`/_layouts/default.html`)
- ✅ Configuration (`_config.yml`, `.gitignore`, `Gemfile`)
- ✅ Documentation (`README.md`, `CHANGELOG.md`, `CITATION.md`, `CONTRIBUTING.md`, `SOURCES.md`)
- ✅ License (`LICENSE`)

---

## Zenodo Deposit Instructions

This release is ready for Zenodo deposit to obtain a permanent DOI.

**Steps:**
1. Copy all metadata from `ZENODO.md` into the Zenodo submission form
2. Upload the GitHub repository or ZIP archive
3. Zenodo will assign a DOI (format: `10.5281/zenodo.XXXXXXX`)
4. After deposit, update `README.md` and `CITATION.md` with the assigned DOI
5. Create a GitHub release linking to the Zenodo DOI

See `ZENODO.md` for complete submission instructions.

---

## Version Numbering & Future Releases

**Versioning:** Semantic Versioning (Major.Minor.Patch)

**Future Planned Updates:**

- **v1.1** — First USCIS policy update or clarification (estimated 2026 Q3–Q4)
  - New RFE patterns if adjudication practice changes
  - Updates to case law if new precedent affects interpretation
  - Community-reported corrections and improvements
  - Possible CI/CD automation for validation

- **v2.0** — Major content expansion or Dhanasar reinterpretation (TBD)
  - Only if significant AAO precedent affects Dhanasar framework
  - Addition of new guidance sections (e.g., visa bulletin strategy)
  - Expanded international context (PT, ES language versions)

Each version receives its own Zenodo DOI. The parent Zenodo DOI remains stable across versions for permanent citation.

---

## Credits

**Author:** Wederson Marinho  
**Maintained by:** ImigraScore (https://imigrascore.us)  
**ORCID:** https://orcid.org/0009-0004-6401-3465  

**Related Work:**
Marinho, W. (2025). *The Complete Guide to EB-2 National Interest Waiver.* SSRN: http://dx.doi.org/10.2139/ssrn.5762365

**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

---

## How to Use This Release

**For GitHub:**
1. Clone: `git clone https://github.com/imigrascore/eb2-niw-framework.git`
2. View locally: `bundle install && bundle exec jekyll serve`
3. Access: http://localhost:4000

**For Zenodo:**
1. Download ZIP from GitHub or Zenodo
2. Extract and view `index.html` locally
3. Or view at: https://imigrascore.github.io/eb2-niw-framework/

**For Citation:**
- See `CITATION.md` for APA, BibTeX, and Chicago formats
- Use Zenodo DOI once assigned

---

**Thank you for using The EB-2 NIW Framework.**  
Questions or improvements? Visit: https://github.com/imigrascore/eb2-niw-framework/issues

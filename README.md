# Research Chemical Sourcing & Analytical Verification Reference

**A Comprehensive Technical Resource for Licensed Laboratories and Procurement Professionals**

**Maintained by Dr. Steve Dale, Director, [Offshore Chemicals](https://offshorechem.com)**

---

## 📋 Table of Contents

- [Introduction: Why Analytical Verification Matters](#introduction)
- [Certificate of Analysis (COA): Structure and Interpretation](#coa)
- [Analytical Methods for Purity Verification](#analytical-methods)
  - [High-Performance Liquid Chromatography (HPLC)](#hplc)
  - [Nuclear Magnetic Resonance (NMR) Spectroscopy](#nmr)
  - [Mass Spectrometry (MS)](#ms)
  - [Karl Fischer Titration](#karl-fischer)
- [Impurity Profiling: Regulatory Framework](#impurity-profiling)
- [Supplier Evaluation Criteria](#supplier-evaluation)
- [Quality Documentation Checklist](#documentation-checklist)
- [Additional Resources](#resources)
- [About Offshore Chemicals](#about)

---

## Introduction: Why Analytical Verification Matters {#introduction}

The credibility of laboratory research depends on the quality of the materials used. For licensed laboratories engaged in pharmaceutical development, chemical synthesis, or analytical method validation, sourcing high-purity research compounds is a critical component of experimental integrity.

Impurities in research compounds can introduce uncontrolled variables that compromise reproducibility, skew experimental results, and jeopardize regulatory submissions. Even trace contaminants can have significant effects on biological assays and analytical measurements.

This repository provides a technical reference for laboratory professionals and procurement specialists involved in sourcing research compounds. It covers analytical verification methods, Certificate of Analysis (COA) interpretation, impurity profiling, and supplier evaluation criteria.

**Research Use Notice:** All information in this repository is provided strictly for laboratory and scientific research purposes. Compounds discussed are intended for research and development applications only. No health, therapeutic, or consumption claims are made or implied.

For a comprehensive overview of quality verification, see our [Laboratory Buyer's Guide to Chemical Purity Verification](https://medium.com/@offshorechemicals/the-laboratory-buyers-guide-to-chemical-purity-verification-c6a4e7b81fda) on Medium.

---

## Certificate of Analysis (COA): Structure and Interpretation {#coa}

Every batch of research compounds should be accompanied by a batch-specific Certificate of Analysis. This document provides the primary evidence of quality and should include the following elements:

| Document Element | Purpose |
|------------------|---------|
| Purity percentage (HPLC/GC verified) | Confirms product meets specifications |
| Analytical method and parameters | Provides transparency on testing methodology |
| Full impurity profile | Identifies all detectable impurities |
| Residual solvent analysis | Verifies solvents within ICH Q3C limits |
| Lot/Batch number | Ensures traceability and batch-specific documentation |
| Retest/Expiry information | Guides proper usage timeline |
| Quality control authorization | Confirms formal approval |

A comprehensive COA should include the actual HPLC chromatogram, not just the numerical purity value. The chromatogram provides a visual representation of sample components. A high-purity compound shows a single major peak with a flat baseline, while additional peaks indicate impurities.

**Red Flag:** If a supplier cannot provide a batch-specific COA before shipment, do not proceed with the order. Any reputable supplier will have this documentation readily available.

For a practical guide to COA interpretation, read our article on [How to Read a Certificate of Analysis](https://offshorechemical.substack.com/p/how-to-read-a-certificate-of-analysis) on Substack.

---

## Analytical Methods for Purity Verification {#analytical-methods}

The most reputable suppliers employ multiple orthogonal analytical techniques to confirm the identity and purity of their compounds. No single analytical method is sufficient.

### High-Performance Liquid Chromatography (HPLC) {#hplc}

HPLC is the gold standard for purity analysis. This technique separates compounds based on their chemical properties and provides a quantitative measure of purity. A typical HPLC analysis reveals:

- The percentage purity of the target compound
- The presence and quantity of any impurities
- The retention time, which confirms compound identity

**Purity Threshold:** A ≥ 98% purity threshold is the accepted minimum for compounds intended for research applications. Compounds with lower purity introduce impurity variables that can confound dose-response relationships.

**Relative Retention Time (RRT):** Impurity positions are reported using RRT, which expresses the retention time of an impurity relative to the main compound. This allows comparison across different analytical runs.

### Nuclear Magnetic Resonance (NMR) Spectroscopy {#nmr}

NMR provides structural confirmation of the compound. This technique analyzes the magnetic properties of atomic nuclei to determine molecular structure. A clean NMR spectrum:

- Confirms the compound is what it claims to be
- Reveals the presence of residual solvents
- Detects certain types of impurities that HPLC might miss

### Mass Spectrometry (MS) {#ms}

Mass spectrometry provides molecular weight confirmation. When combined with HPLC (LC-MS), this technique offers both purity and identity verification in a single analysis.

**High-Resolution Mass Spectrometry (HRMS):** HRMS measures mass with extremely high accuracy (typically to four or more decimal places), distinguishing between compounds with the same nominal mass but different elemental compositions.

### Karl Fischer Titration {#karl-fischer}

Karl Fischer titration determines water content in research compounds. This is particularly important for hygroscopic materials, where absorbed moisture can affect:

- Accurate mass measurement
- Stock solution preparation
- Compound stability

A result of < 1% water content is the accepted standard for research-grade hydrochloride (HCl) salt compounds.

For more detailed analytical resources, visit our [GitHub repository](https://github.com/OffshoreChemicals/analytical-chemistry-resources).

---

## Impurity Profiling: Regulatory Framework {#impurity-profiling}

The International Council for Harmonisation (ICH) provides the global framework for impurity control. Three guidelines are particularly relevant:

### ICH Q3A: Organic Impurities

| Threshold | Concentration | Action Required |
|-----------|---------------|-----------------|
| Reporting | ≥ 0.05% | Impurity must be reported on COA |
| Identification | ≥ 0.10% | Impurity structure must be identified |
| Qualification | ≥ 0.15% | Impurity must undergo toxicological assessment |

### ICH Q3C: Residual Solvents

| Class | Description | Examples | Permitted Daily Exposure |
|-------|-------------|----------|--------------------------|
| Class 1 | Solvents to avoid | Benzene, Carbon tetrachloride | ≤ 2 ppm |
| Class 2 | Solvents to limit | Acetonitrile, Methanol | Varies by solvent |
| Class 3 | Low toxicity | Ethanol, Acetone | ≤ 5000 ppm |

### ICH Q3D: Elemental Impurities

Metal catalysts such as Palladium, Platinum, and Nickel are commonly used in organic synthesis. ICH Q3D provides guidance on controlling these elemental impurities. Inductively Coupled Plasma-Mass Spectrometry (ICP-MS) is the standard technique for detection.

For our complete guide on sourcing compliance, see the [Sourcing High-Purity Research Compounds](https://offshorechemicals.blogspot.com/2026/09/sourcing-high-purity-research-compounds.html) article on Blogger.

---

## Supplier Evaluation Criteria {#supplier-evaluation}

When evaluating potential suppliers of research chemicals, procurement professionals should apply a systematic verification framework.

### Eight Quality Criteria

| Criterion | What to Demand | Why It Matters |
|-----------|----------------|----------------|
| **Third-Party Verification** | Independent analytical data | Eliminates bias, validates claims |
| **Purity Minimums** | ≥ 98% for research compounds | Lower purity introduces variables |
| **Batch Consistency** | Historical data across batches | Reduces experimental variability |
| **Complete Documentation** | COA, MSDS, analytical data | Enables quality assessment |
| **Traceability** | Manufacturing records, lot numbers | Links issues to specific batches |
| **Stability Data** | Storage conditions, retest dates | Ensures compound integrity |
| **Supply Chain Transparency** | Manufacturing location, sourcing | Reduces counterfeit risk |
| **Regulatory Compliance** | ICH guideline adherence | Meets quality benchmarks |

### Questions to Ask Before Ordering

1. Can you provide a batch-specific COA?
2. What analytical methods were used for purity verification?
3. Are residual solvents within ICH Q3C limits?
4. How do you handle batch traceability?
5. Do you provide ongoing technical support?

For a downloadable checklist, visit our [Issuu publication](https://issuu.com/offshorechemicals/docs/the_laboratory_buyers_guide_to_chemical_purity_ver).

---

## Quality Documentation Checklist {#documentation-checklist}

Before accepting any shipment of research compounds, verify that the following documentation is included:

- [ ] Batch-specific Certificate of Analysis (COA)
- [ ] HPLC chromatogram with purity data
- [ ] Impurity profile listing all detected impurities
- [ ] Residual solvent analysis (HS-GC results)
- [ ] Elemental impurity data (if applicable)
- [ ] Material Safety Data Sheet (MSDS)
- [ ] Storage and handling recommendations
- [ ] Retest/expiry date
- [ ] Quality control authorization signature

For more insights on supplier evaluation, subscribe to our [Substack newsletter](https://substack.com/@offshorechemical).

---

## Additional Resources {#resources}

This repository is part of a broader collection of educational resources for the research community.

| Resource | Description | Link |
|----------|-------------|------|
| **Laboratory Buyer's Guide** | Comprehensive sourcing and quality verification guide | [Medium](https://medium.com/@offshorechemicals/the-laboratory-buyers-guide-to-chemical-purity-verification-c6a4e7b81fda) |
| **COA Interpretation Guide** | Practical guide to reading Certificates of Analysis | [Substack](https://offshorechemical.substack.com/p/how-to-read-a-certificate-of-analysis) |
| **Sourcing Guide** | Five essential questions for supplier evaluation | [Blogger](https://offshorechemicals.blogspot.com/2026/09/sourcing-high-purity-research-compounds.html) |
| **Impurity Profiling Guide** | Extended article on ICH guidelines and analytical methods | [Medium](https://medium.com/@offshorechemicals/understanding-impurity-profiling-in-research-compounds-a-guide-for-laboratory-professionals-9b1e7357ef8f) |
| **PDF Guide** | Downloadable resource for procurement teams | [Issuu](https://issuu.com/offshorechemicals/docs/the_laboratory_buyers_guide_to_chemical_purity_ver) |
| **Presentations** | Educational presentations on analytical verification | [Speaker Deck](https://speakerdeck.com/offshorechemicals) |
| **Company Website** | Product catalog and company information | [Offshore Chemicals](https://offshorechem.com) |
| **Author Profile** | Professional profile and contact | [About.me](https://about.me/drstevedale) |
| **Article Archive** | Collection of published articles | [IndiBlogHub](https://indibloghub.com/creators/offshorechemicals) |

---

## About Offshore Chemicals {#about}

**[Offshore Chemicals](https://offshorechem.com)** is a dedicated partner for the research community, supplying high-purity research compounds to licensed laboratories worldwide.

Our commitment to quality is underpinned by:

- **Comprehensive Documentation:** Every shipment includes a detailed Certificate of Analysis (COA) with HPLC purity data, impurity profiles, and residual solvent analysis
- **Third-Party Verification:** All compounds undergo independent, accredited testing to verify purity and identity
- **Supply Chain Transparency:** Full traceability from manufacturer to laboratory
- **Technical Support:** Experienced scientists available for compound handling and analytical guidance

### About the Author

**Dr. Steve Dale** is the Director of Offshore Chemicals. With a PhD in Chemistry and over a decade of experience in analytical method development and chemical sourcing, he is committed to supporting scientific research through transparent, documented supply chains.

**Connect with Dr. Dale:**
- [About.me](https://about.me/drstevedale)
- [IndiBlogHub](https://indibloghub.com/creators/offshorechemicals)
- [Speaker Deck](https://speakerdeck.com/offshorechemicals)

---

## 📝 Repository Information

**Repository:** Research Chemical Sourcing & Analytical Verification Reference

**Purpose:** This repository provides educational resources for licensed research laboratories and procurement professionals involved in sourcing high-purity chemical compounds for research and development applications.

**Content Focus:** Quality verification, analytical methods (HPLC, NMR, MS), COA interpretation, impurity profiling, supplier evaluation, and regulatory compliance.

**Audience:** Research scientists, laboratory managers, procurement professionals, and students in chemistry and related fields.

---

*This repository is maintained by [Offshore Chemicals](https://offshorechem.com) as a service to the research community. All content is for educational and research purposes only.*

## some products
[GHB](https://offshorechem.com/product/gamma-hydroxybutyrate/)
[Nasal spray](https://offshorechem.com/product/ketamine-nasal-spray/)
[Alpha](https://offshorechem.com/product/alpha-pvp/)

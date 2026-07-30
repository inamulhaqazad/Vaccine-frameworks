# Vaccine Design Frameworks: Existing Technologies and References

This document summarizes three antigen-design frameworks — **epitope-based**, **region/domain-based**, and **sequence-based** — and maps each to *licensed or clinically deployed* vaccines (not proposed/preclinical designs only), with the underlying technology platform and primary references.

---

## Framework definitions (for context)

| Framework | Design logic |
|---|---|
| **Epitope-based** | Vaccine built from minimal immunogenic determinants (short B- or T-cell peptide epitopes), typically selected via immunoinformatics/experimental epitope mapping. |
| **Region/domain-based** | Vaccine built from a defined structural region of a larger antigen (a domain, conformational state, or self-assembling subunit) rather than the whole protein or whole pathogen. |
| **Sequence-based** | Vaccine antigen selected or encoded directly from genomic/proteomic sequence data — either by mining a pathogen's genome for candidate ORFs ("reverse vaccinology") or by delivering the full-length gene/mRNA sequence of a chosen antigen via a nucleic-acid or vector platform. |

---

## 1. Sequence-based framework

| Vaccine (brand) | Pathogen | Technology platform | Design basis | Regulatory status |
|---|---|---|---|---|
| **Bexsero** (4CMenB) | *Neisseria meningitidis* serogroup B | Recombinant multi-protein subunit | Whole-genome mining of strain MC58 for surface-exposed ORFs — the founding "reverse vaccinology" vaccine | Licensed in 30+ countries incl. EU, UK (NIP), Australia, Canada, USA |
| **Trumenba** | *N. meningitidis* serogroup B | Recombinant protein subunit | Proteomics-based (rather than genomics-based) antigen selection | FDA/EMA licensed |
| **Comirnaty** (BNT162b2) / **Spikevax** (mRNA-1273) | SARS-CoV-2 | mRNA–lipid nanoparticle | Full-length, prefusion-stabilized spike gene sequence taken directly from the viral genome | FDA/EMA full approval |
| **ZyCoV-D** | SARS-CoV-2 | Plasmid DNA (needle-free intradermal) | Full-length spike gene selected from the Wuhan-Hu-1 reference genome (GenBank MN908947.3) | India DCGI emergency use authorization (world's first licensed DNA vaccine) |
| **Ervebo** (rVSV-ΔG-ZEBOV-GP) | *Zaire ebolavirus* | Live recombinant viral vector (VSV backbone) | Ebola glycoprotein gene sequence substituted for the VSV glycoprotein gene | FDA/EMA licensed, WHO-prequalified |

**References**
1. Rappuoli R. Reverse vaccinology, a genome-based approach to vaccine development. *Vaccine* / review indexed PubMed ID 12517268.
2. Serruto D, et al. Bexsero: a multicomponent vaccine for prevention of meningococcal disease. Overview of 4CMenB antigen composition (fHbp, NadA, NHBA, OMV) derived from MC58 genome sequencing.
3. Rossi R, et al. Novel approaches to *Neisseria meningitidis* vaccine design. *Pathogens and Disease*, 2017 (comparative history of Bexsero/reverse vaccinology and Trumenba/proteomics). https://academic.oup.com/femspd/article/75/3/ftx033/3078540
4. Metz B, et al. / EMA Spikevax product information — mRNA encoding prefusion-stabilized (2P) spike, EMA SmPC. https://ec.europa.eu/health/documents/community-register/2021/20211004153286/anx_153286_en.pdf
5. CDSCO. ZyCoV-D Summary of Product Characteristics — plasmid DNA vaccine, spike gene from Wuhan-Hu-1 isolate. https://cdsco.gov.in/opencms/resources/UploadCDSCOWeb/2018/UploadSmPC/6.%20ZyCoVD%203mg_Cadila_SmPC,%20Factsheet,%20PI.pdf
6. Mallapaty S. India's DNA COVID vaccine is a world first — more are coming. *Nature* news, 2021.
7. ACIP. Use of Ebola Vaccine: Recommendations of the Advisory Committee on Immunization Practices, United States, 2020. *MMWR*. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7802368/
8. EMA. Ervebo (Ebola Zaire Vaccine, rVSVΔG-ZEBOV-GP) product information. https://www.ema.europa.eu/en/documents/product-information/ervebo-epar-product-information_en.pdf

---

## 2. Region/domain-based framework

| Vaccine (brand) | Pathogen | Technology platform | Design basis | Regulatory status |
|---|---|---|---|---|
| **Arexvy** / **Abrysvo** | RSV | Recombinant protein subunit | Structurally stabilized **prefusion conformation** of the F glycoprotein (derived from the DS-Cav1 design: engineered disulfide bond + cavity-filling mutations) | FDA/EMA licensed (older adults; Abrysvo also maternal) |
| **mResvia** (mRNA-1345) | RSV | mRNA–LNP | mRNA encoding the same prefusion-stabilized F domain concept (DS2, an enhanced DS-Cav1 derivative) | FDA/EMA licensed |
| **Shingrix** | Varicella zoster virus (shingles) | Recombinant protein subunit + AS01B adjuvant | Single domain: the extracellular ectodomain of glycoprotein E (gE) | FDA/EMA licensed |
| **Gardasil / Gardasil-9 / Cervarix** | HPV | Virus-like particle (VLP) | Self-assembling **L1 major capsid protein** region only (no viral DNA) | FDA/EMA licensed |
| **Recombivax HB / Engerix-B** | Hepatitis B virus | Recombinant protein subunit (yeast-expressed) | Hepatitis B **surface antigen (HBsAg)** region only, lacking the preS domain present in native virion | FDA licensed 1986 (Recombivax HB — first licensed recombinant-DNA vaccine of any kind); Engerix-B licensed 1989 |

**References**
1. RSV Vaccines: Targeting Prefusion F and G Proteins from Structural Design to Clinical Application. *Viruses/MDPI*, 2025. https://www.mdpi.com/2076-393X/13/11/1133
2. Rational design of respiratory syncytial virus dimeric F-subunit vaccines in protein and mRNA forms (describes DS-Cav1 → Arexvy, and DS2 → mResvia lineage). https://www.biorxiv.org/content/10.1101/2025.05.31.655981.full.pdf
3. Hydrophobic residue substitutions enhance the stability and in vivo immunogenicity of RSV fusion protein. *J Virol*. https://journals.asm.org/doi/10.1128/jvi.00087-25
4. Rational design of uncleaved prefusion-closed trimer vaccines for RSV and metapneumovirus. *Nature Communications*, 2024. https://www.nature.com/articles/s41467-024-54287-x
5. Structures of the Varicella Zoster Virus Glycoprotein E and Epitope Mapping of Vaccine-Elicited Antibodies (confirms gE is the sole Shingrix antigen). https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11511291/
6. Recombinant Glycoprotein E of VZV Contains Glycan-Peptide Motifs That Modulate B Cell Epitopes. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6412795/
7. Capsid Protein L1 overview — Gardasil/Cervarix VLP composition. *ScienceDirect Topics*. https://www.sciencedirect.com/topics/neuroscience/capsid-protein-l1
8. Strain-specific differences in purification and VLP formation for a quadrivalent recombinant HPV vaccine. *ScienceDirect*, 2024.
9. Recombinant Hepatitis B Vaccine — overview, licensure history (Recombivax HB 1986, Engerix-B 1989). *ScienceDirect Topics*. https://www.sciencedirect.com/topics/pharmacology-toxicology-and-pharmaceutical-science/recombinant-hepatitis-b-vaccine
10. FDA Approves a Genetically Engineered Vaccine for Hepatitis B. *EBSCO Research Starters*.

---

## 3. Epitope-based framework

This is the framework with the **weakest track record of full licensure for human infectious-disease prevention** — worth flagging explicitly given how central epitope selection is to your own HCV pipeline. Peptide/epitope vaccines remain, almost without exception, investigational for human infectious disease and oncology; none has cleared FDA approval to date. WHO nonetheless maintains manufacturing/QC guidance for the class, reflecting sustained development interest.

| Vaccine / candidate | Pathogen | Technology platform | Design basis | Regulatory status |
|---|---|---|---|---|
| **UB-612** (Vaxxinity/COVAXX) | SARS-CoV-2 | Hybrid "multitope" protein + synthetic peptide | S1-RBD-Fc fusion protein (B-cell epitope, domain-based) **plus** five synthetic Th/CTL peptide epitopes from conserved N, M, and S2 regions, plus a proprietary UBITh1a helper peptide, on CpG1/Adjuphos adjuvant | Furthest-advanced human epitope-inclusive candidate to date: positive Phase 3 head-to-head booster data (vs. BNT162b2, ChAdOx1-S, BIBP) in late 2022; rolling submission to UK MHRA initiated Sept 2022. No confirmed full licensure/EUA found as of the most recent information available to me — worth verifying directly if you need current status. |
| **B2T / B2T-TB2 dendrimer peptides** | Foot-and-mouth disease virus (veterinary) | Synthetic multi-epitope peptide dendrimer (B-cell epitope + T-cell epitope) | Combines a VP1 neutralizing B-cell epitope with a T-helper epitope on a branched peptide scaffold | Most clinically/field-advanced *purely* peptide (non-hybrid) platform; used experimentally and in some emergency-response contexts, not broadly commercially licensed like conventional inactivated FMD vaccines |
| Multiple early VP1-based synthetic peptides (1980s–2000s, China/Europe) | FMDV | Synthetic peptide ± carrier fusion | VP1 neutralizing loop epitope, later combined with T-helper epitopes to overcome weak immunogenicity in outbred livestock | Field-tested at scale in some regions; largely superseded by inactivated and recombinant subunit vaccines |

Note: strictly speaking, **no purely peptide-only human infectious-disease vaccine has reached full licensure** — UB-612 is the closest real-world case, but it achieves broad B-cell coverage through a conventional RBD-Fc subunit domain and reserves the "epitope-based" logic for the T-cell component only. That split (domain-based B-cell antigen + epitope-based T-cell payload) is itself a useful design precedent.

**References**
1. WHO. Synthetic peptide vaccines — norms and standards for development, production, and control. https://www.who.int/teams/health-product-policy-and-standards/standards-and-specifications/norms-and-standards/vaccine-standardization/synthetic-peptide-vaccines
2. How many FDA-approved synthetic peptide vaccines are there? *PatSnap*, 2025 — confirms no FDA-approved human peptide-only vaccine currently exists; all remain investigational. https://synapse.patsnap.com/article/how-many-fda-approved-synthetic-peptide-vaccine-are-there
3. UB-612, a Multitope Universal Vaccine Eliciting a Balanced B and T Cell Immunity against SARS-CoV-2 Variants of Concern. *medRxiv*, 2022 (describes the S1-RBD-sFc + Th/CTL peptide construct). https://www.medrxiv.org/content/10.1101/2022.04.11.22272364v1.full
4. Safety and immunogenicity of UB-612 heterologous booster in adults primed with mRNA, adenovirus, or inactivated COVID-19 vaccines: a randomized, active-controlled, Phase 3 trial. *PMC*. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12301762/
5. Vaxxinity Announces Positive Topline Pivotal Phase 3 COVID-19 Booster Data for UB-612, Dec 2022. https://ir.vaxxinity.com/news-releases/news-release-details/vaxxinity-announces-positive-topline-pivotal-phase-3-covid-19
6. Vaxxinity Initiates Rolling Submission for UB-612 COVID-19 Vaccine with MHRA (UK), Sept 2022. https://ir.vaxxinity.com/news-releases/news-release-details/vaxxinity-initiates-rolling-submission-ub-612-covid-19-vaccine
3. Single dose of foot-and-mouth disease peptide vaccine fully protects swine and achieves intraserotype crossed neutralization (B2T-TB2 dendrimer). *PMC*, 2025. https://pmc.ncbi.nlm.nih.gov/articles/PMC12500866/
4. Wang CY, et al. Effective synthetic peptide vaccine for foot-and-mouth disease in swine. *Vaccine*, 2002;20:2603–2610.
5. Rodriguez A, et al. *Virology*, 1994;205:24–33; Taboga O, et al. *J Virol*, 1997;71:2606–2614 — cattle/swine immunogenicity limitations of VP1-only peptide constructs.
6. Cao Y, et al. Rational design and efficacy of a multi-epitope recombinant protein vaccine against FMDV serotype A in pigs. *Antiviral Res*, 2017;140:133–141.

---

## Quick synthesis

- **Sequence-based** design has the most direct translation to fully licensed human products, largely because it now overlaps with mRNA/DNA/vector platforms that deliver a complete antigen-encoding sequence rather than a minimized fragment.
- **Region/domain-based** design is the dominant paradigm behind the most successful modern subunit vaccines (RSV, shingles, HPV, hepatitis B) — the common thread is picking one structurally well-defined, highly immunogenic domain rather than the full antigen or full epitope repertoire.
- **Epitope-based** design is comparatively immature in terms of licensure for infectious disease, largely due to weak intrinsic immunogenicity of short peptides and the need for careful T-helper epitope pairing/adjuvanting. UB-612 is the clearest counterexample — it reached Phase 3 head-to-head trials against three authorized vaccine platforms and a regulatory submission — but even there, the peptide/epitope component was used only for the T-cell payload, riding alongside a conventional domain-based (RBD-Fc) B-cell antigen rather than replacing it. That pattern is directly relevant to justifying multi-objective epitope selection (conservation, immunodominance, HLA coverage) as a way of strengthening the epitope component rather than assuming epitopes alone can carry a whole vaccine.


# Structure of the Review

## From Gemini 3.0 Pro

This is an excellent topic for a bachelor thesis, as Multi-Parton Scattering (MPS) is a fascinating and complex area at the intersection of perturbative and non-perturbative QCD, with significant implications for both Standard Model measurements and searches for new physics. Given your existing knowledge, the key will indeed be *organization* and *synthesis*.

Here's a comprehensive structure for your review, followed by writing guidelines, with a specific emphasis on how to organize the studies you're familiar with and connect them to your J/psi+J/psi+phi research.

---

## Review Structure: Multi-Parton Scattering in High-Energy Proton-Proton Collisions

**Title Suggestion:** "Multi-Parton Scattering in High-Energy Proton-Proton Collisions: A Review of Theoretical Frameworks, Experimental Measurements, and Phenomenological Implications" (or something similar, tailored to your focus).

---

### 1. Abstract

*   Briefly state the importance of MPS in high-energy proton-proton collisions.
*   Mention its role as both a background and a probe of proton structure.
*   Summarize the key theoretical concepts (e.g., DPDFs, $\sigma_{eff}$).
*   Highlight the diversity of experimental measurements across various final states and energies.
*   Conclude with the current understanding, open questions, and the relevance of MPS to complex final states like J/psi+J/psi+phi.

### 2. Introduction

*   **2.1. The Standard Model and Proton-Proton Collisions:**
    *   Briefly introduce the LHC (or other relevant colliders) and the goal of probing fundamental interactions.
    *   Define single parton scattering (SPS) as the dominant process.
*   **2.2. What is Multi-Parton Scattering (MPS)?**
    *   Define MPS (multiple hard parton-parton interactions within a single proton-proton collision).
    *   Illustrate with a simple diagram (e.g., two partons from proton A, two from proton B, undergoing two distinct hard scatters).
    *   Distinguish between Double Parton Scattering (DPS), Triple Parton Scattering (TPS), etc.
*   **2.3. Why is MPS Important?**
    *   **Background to SM Measurements and New Physics Searches:** Explain how MPS can mimic or contribute to complex final states, making it a crucial background to understand (e.g., multi-jet, multi-boson, multi-heavy-flavor production).
    *   **Probe of Proton Structure:** MPS provides unique insights into the spatial and momentum correlations of partons within the proton, going beyond standard PDFs.
    *   **Understanding the Underlying Event (UE):** MPS is an integral part of the non-perturbative activity in a collision.
*   **2.4. Scope of the Review:**
    *   Clearly state what the review will cover: theoretical foundations, experimental techniques and results, phenomenological implications, and future directions.
    *   **Explicitly link to your research:** "This review will pay particular attention to MPS in heavy quark production, setting the stage for understanding complex final states such as J/psi+J/psi+phi, which are central to the author's bachelor thesis research at CMS."

### 3. Theoretical Framework of MPS

*   **3.1. Factorization and the Concept of Independent Scatters:**
    *   Introduce the factorization hypothesis for SPS.
    *   Extend this to MPS, assuming independent hard scatters.
    *   Discuss the limitations and potential breakdown of this independence (e.g., parton correlations).
*   **3.2. Double Parton Distribution Functions (DPDFs):**
    *   **Definition:** Explain what DPDFs are (probability of finding two partons with specific momentum fractions $x_1, x_2$ and transverse separation $\vec{b}$).
    *   **Non-perturbative Nature:** Emphasize that DPDFs are non-perturbative and currently not directly calculable from first principles.
    *   **Modeling:** Discuss common phenomenological models for DPDFs (e.g., product of two single PDFs, with spatial correlation terms).
    *   **Challenges:** Highlight the difficulties in constraining DPDFs due to their multi-dimensional nature (momentum, spatial, spin correlations).
    *   **Connection to GPDs:** Briefly mention how Generalized Parton Distributions (GPDs) provide spatial information about partons and can inform DPDF models.
*   **3.3. The Effective Cross-Section ($\sigma_{eff}$):**
    *   **Definition and Derivation:** Explain the formula $\sigma_{DPS} = \frac{\sigma_1 \sigma_2}{\sigma_{eff}}$ (for two processes $\sigma_1, \sigma_2$).
    *   **Physical Interpretation:** Relate $\sigma_{eff}$ to the effective transverse area of the proton where hard scatters can occur.
    *   **Universality (or lack thereof):** Discuss the expectation that $\sigma_{eff}$ should be universal, but how experimental results often show some dependence on final state, energy, and kinematic cuts.
*   **3.4. Higher-Order MPS (TPS, QPS):**
    *   Briefly introduce the concept of Triple Parton Scattering (TPS) and higher orders.
    *   Provide the analogous formula for TPS (e.g., $\sigma_{TPS} = \frac{\sigma_1 \sigma_2 \sigma_3}{\sigma_{eff}^2}$).
    *   Discuss the rapidly increasing complexity and smaller cross-sections, making them harder to measure.
*   **3.5. Implementation in Monte Carlo Event Generators:**
    *   Describe how MPS is modeled in generators like Pythia, Herwig, and Sherpa.
    *   Discuss the underlying assumptions and models used for DPDFs and $\sigma_{eff}$ in these tools.
    *   Mention the limitations and uncertainties inherent in these simulations.

### 4. Experimental Measurements of MPS

This is where you'll organize the "plenty of experimental studies" you know. The most effective way is **by final state**, as different final states probe different parton kinematics and types (gluons, quarks).

*   **4.1. General Experimental Signatures and Techniques:**
    *   **Kinematic Signatures:** Multiple hard objects, often with minimal kinematic correlation between the two hard sub-systems (e.g., transverse momentum balance).
    *   **Event Selection:** How are MPS events isolated from SPS events? (e.g., requiring two distinct hard scales, specific rapidity gaps).
    *   **Background Subtraction:** Discuss methods for disentangling MPS from SPS backgrounds.
    *   **Observables:** How $\sigma_{eff}$ is extracted, differential measurements (e.g., dependence on $\Delta\phi$ between sub-systems, $p_T$ of sub-systems).
*   **4.2. Overview of Experimental Results (Organizing Principle: Final State & Energy):**

    *   **A. Di-jet + Di-jet Production (The "Classic" MPS Measurement):**
        *   **Early Measurements:** CDF, D0 at Tevatron. Discuss how these first established the existence of MPS and measured $\sigma_{eff}$.
        *   **LHC Measurements:** ATLAS, CMS at 7, 8, 13 TeV. Discuss how these refined the measurements, explored kinematic dependencies, and tested the universality of $\sigma_{eff}$.
        *   **Key Findings:** What values of $\sigma_{eff}$ were obtained? How did they compare?
    *   **B. Jet + Photon/W/Z + Jet Production:**
        *   Measurements involving electroweak bosons or photons alongside jets (e.g., $\gamma+2j$, $W+2j$, $Z+2j$).
        *   Discuss how these probe different parton combinations (e.g., quark-gluon, quark-quark).
        *   Compare $\sigma_{eff}$ values to di-jet measurements.
    *   **C. Heavy Flavor Production (Crucial for your research!):**
        *   **Di-b-jet Production:** (e.g., CMS, ATLAS). Discuss how heavy quark production (often dominated by gluon fusion at low $x$) can be a strong channel for MPS.
        *   **J/psi + J/psi Production:** (LHCb, CMS, ATLAS).
            *   **Detail existing measurements:** Describe the experimental techniques, observed cross-sections, and how the MPS contribution was estimated/measured.
            *   **Discuss the large MPS fraction:** Emphasize why MPS is often a dominant contributor to such final states (e.g., due to the large gluon density at low $x$).
            *   **Compare $\sigma_{eff}$ values:** How do they compare to light-jet measurements? Are there differences? Why?
        *   **Other Heavy Flavor:** (e.g., $D^0+D^0$, $B_c$ production).
    *   **D. Multi-Boson Production:**
        *   (e.g., $W+W$, $W+Z$, $Z+Z$, $\gamma+\gamma$).
        *   Discuss the challenges of measuring MPS in these channels due to smaller cross-sections and complex SPS backgrounds.
        *   Mention any observed MPS contributions.
    *   **E. Other Exotic Final States:**
        *   Briefly mention any other interesting or novel MPS measurements (e.g., $4\gamma$ production).
*   **4.3. Consistency and Discrepancies Across Measurements:**
    *   **Universality of $\sigma_{eff}$:** Synthesize the findings. Is $\sigma_{eff}$ truly universal? What are the observed ranges?
    *   **Dependence on Kinematics/Final State:** Discuss any observed dependencies (e.g., on the scale of the hard scatters, rapidity, parton type).
    *   **Theoretical Interpretation of Discrepancies:** How do these discrepancies inform DPDF models and our understanding of parton correlations?
    *   **Role of Non-Perturbative Effects:** Discuss the impact of color connections and other non-perturbative effects.

### 5. Phenomenological Implications and Applications

*   **5.1. Probing Proton Structure and Parton Correlations:**
    *   How MPS measurements constrain DPDFs and provide information on the spatial distribution of partons.
    *   The potential to extract information on parton correlations (e.g., spin, transverse momentum).
*   **5.2. Background to Standard Model Measurements:**
    *   Discuss specific SM measurements where MPS is a significant background (e.g., $t\bar{t} + \text{jets}$, multi-boson production).
    *   The importance of accurate MPS modeling for precision measurements.
*   **5.3. Background to New Physics Searches:**
    *   Explain how MPS can mimic signatures of new physics (e.g., exotic multi-jet final states, searches for new heavy resonances decaying to multiple objects).
    *   The need for robust MPS predictions in searches.
*   **5.4. Understanding the Underlying Event (UE):**
    *   Reiterate the connection between MPS and the UE.
    *   How MPS models contribute to a more complete picture of hadronic interactions.
*   **5.5. Direct Relevance to J/psi+J/psi+phi Production:**
    *   **Synthesize:** Bring together the theoretical understanding and experimental results, particularly from heavy flavor MPS.
    *   **Hypothesize/Discuss:** Explain why MPS is expected to be a significant, if not dominant, contribution to J/psi+J/psi+phi.
        *   Multiple heavy quarks (J/psi contains $c\bar{c}$).
        *   Phi meson contains $s\bar{s}$.
        *   These often arise from gluon-initiated processes at lower $x$, where DPDFs are larger.
    *   **Challenges:** Discuss the specific experimental challenges in disentangling SPS from MPS for such a complex final state (e.g., combinatorial background, reconstruction efficiency).
    *   **Contribution of your research:** How will your specific analysis contribute to the broader understanding of MPS in heavy quark production and potentially constrain DPDFs?

### 6. Summary and Outlook

*   **6.1. Key Takeaways:**
    *   Recap the importance of MPS.
    *   Summarize the current status of theoretical understanding (DPDFs, $\sigma_{eff}$).
    *   Highlight the breadth and depth of experimental measurements, and the observed trends/discrepancies.
*   **6.2. Open Questions and Challenges:**
    *   The universality (or lack thereof) of $\sigma_{eff}$.
    *   Precise determination and modeling of DPDFs.
    *   Understanding higher-order MPS processes (TPS, etc.).
    *   The role of non-perturbative effects and color correlations.
*   **6.3. Future Directions:**
    *   **Experimental:** More precise measurements at the LHC (Run 3, HL-LHC) in various final states. New measurements at future colliders (e.g., Electron-Ion Collider for DPDFs).
    *   **Theoretical:** Development of more sophisticated DPDF models, potentially incorporating NLO corrections. Better integration of MPS into event generators.
    *   **Specific to your research:** "Future studies, including analyses of J/psi+J/psi+phi production, will be crucial for further refining our understanding of MPS, particularly in the heavy quark sector, and for providing stringent tests of DPDF models."

### 7. References

*   A comprehensive list of all cited theoretical papers, experimental results, and review articles.

---

## Writing Guidelines for Your Review

1.  **Clarity and Precision:**
    *   **Define all terms:** Assume your reader is a fellow physics student, but not necessarily an expert in MPS. Define acronyms (SPS, MPS, DPS, DPDF, GPD, $\sigma_{eff}$, UE, etc.) upon first use.
    *   **Use clear and concise language:** Avoid overly complex sentences or jargon where simpler alternatives exist.
    *   **Be quantitative:** When discussing experimental results, include values (e.g., $\sigma_{eff}$ values, cross-sections) and their uncertainties.

2.  **Logical Flow and Cohesion:**
    *   **Strong Introduction:** Clearly state the purpose and scope of your review.
    *   **Smooth Transitions:** Ensure a logical flow between paragraphs and sections. Use transition words and phrases to guide the reader.
    *   **Build the narrative:** Start with fundamental concepts and gradually move to more complex theories and experimental details.
    *   **Connect back to your research:** Regularly remind the reader why MPS is relevant to your specific J/psi+J/psi+phi analysis. This is your unique angle.

3.  **Critical Analysis and Synthesis:**
    *   **Don't just list results:** Discuss the *implications* of the findings. Why are certain results important? What do they tell us about the proton or QCD?
    *   **Highlight discrepancies and challenges:** Where do theory and experiment disagree? What are the limitations of current models or measurements? This shows critical thinking.
    *   **Compare and contrast:** When discussing different experimental measurements, compare their $\sigma_{eff}$ values, the final states, and the energies. Discuss why they might be similar or different.
    *   **Synthesize information:** Bring together information from different sources to form a coherent picture. For example, how do di-jet MPS measurements inform heavy-flavor MPS?

4.  **Academic Tone:**
    *   **Objective and Impartial:** Present information fairly, even when discussing conflicting results.
    *   **Formal Language:** Avoid colloquialisms or overly casual phrasing.
    *   **Cite everything:** Every claim, every piece of data, every theoretical concept that isn't common knowledge in particle physics must be attributed to its source. Use a consistent citation style.

5.  **Figures and Tables:**
    *   **Essential for a review:** Include well-chosen figures and tables to illustrate concepts and summarize data.
    *   **Examples:**
        *   Diagrams of SPS vs. MPS.
        *   Plots of $\sigma_{eff}$ values from different experiments/final states vs. energy.
        *   Examples of event displays or kinematic distributions from MPS analyses.
        *   Tables summarizing key $\sigma_{eff}$ measurements.
    *   **Always explain:** Every figure and table must have a clear caption and be referenced and discussed in the main text.

6.  **Self-Correction and Feedback:**
    *   **Proofread meticulously:** Check for grammar, spelling, punctuation, and typographical errors.
    *   **Read aloud:** This often helps catch awkward phrasing or unclear sentences.
    *   **Get feedback:** Ask your supervisor, fellow students, or even a non-physicist friend to read parts of your review. Fresh eyes can spot issues you've overlooked.

By following this structure and these guidelines, you'll be able to produce a comprehensive, insightful, and well-organized review of MPS that effectively leverages your existing knowledge and directly supports your bachelor thesis research. Good luck!

```tex
@article{aaboudMeasurementPrompt$$psi2017,
  title = {Measurement of the Prompt {{J}}/\$\$\textbackslash psi \$\$pair Production Cross-Section in Pp Collisions at \$\$\textbackslash sqrt\textbraceleft s\textbraceright{} = 8\$\$~{{TeV}} with the {{ATLAS}} Detector},

  year = 2017,
  month = feb,
  journal = {The European Physical Journal C},
  volume = {77},
  number = {2},
  pages = {76--110},
  issn = {1434-6052},
  doi = {10.1140/epjc/s10052-017-4644-9},
  urldate = {2025-12-19},
  abstract = {The production of two prompt \$\$J/\textbackslash psi \$\$mesons, each with transverse momenta \$\$p\_\textbraceleft\textbackslash mathrm \textbraceleft T\textbraceright\textbraceright{$>$}8.5\$\$~GeV and rapidity \$\$\textbar y\textbar{} {$<$} 2.1\$\$, is studied using a sample of proton-proton collisions at \$\$\textbackslash sqrt\textbraceleft s\textbraceright{} = 8\$\$~TeV, corresponding to an integrated luminosity of 11.4~fb\$\$\textasciicircum\textbraceleft -1\textbraceright\$\$collected in 2012 with the ATLAS detector at the LHC. The differential cross-section, assuming unpolarised \$\$J/\textbackslash psi \$\$production, is measured as a function of the transverse momentum of the lower-\$\$p\_\textbraceleft\textbackslash mathrm \textbraceleft T\textbraceright\textbraceright\$\$\$\$J/\textbackslash psi \$\$meson, di-\$\$J/\textbackslash psi \$\$\$\$p\_\textbraceleft\textbackslash mathrm \textbraceleft T\textbraceright\textbraceright\$\$and mass, the difference in rapidity between the two \$\$J/\textbackslash psi \$\$mesons, and the azimuthal angle between the two \$\$J/\textbackslash psi \$\$mesons. The fraction of prompt pair events due to double parton scattering is determined by studying kinematic correlations between the two \$\$J/\textbackslash psi \$\$mesons. The total and double parton scattering cross-sections are compared with predictions. The effective cross-section of double parton scattering is measured to be \$\$\textbackslash sigma \_\textbraceleft\textbackslash mathrm \textbraceleft eff\textbraceright\textbraceright{} = 6.3 \textbackslash pm 1.6 \textbackslash mathrm \textbraceleft (stat)\textbraceright{} \textbackslash pm 1.0 \textbackslash mathrm \textbraceleft (syst)\textbraceright\$\$~mb.},
  langid = {english}
}

@article{aaboudStudyHardDoubleparton2016,
  title = {Study of Hard Double-Parton Scattering in Four-Jet Events in Pp Collisions at \$\$ \textbackslash sqrt\textbraceleft s\textbraceright =7 \$\${{TeV}} with the {{ATLAS}} Experiment},

  year = 2016,
  month = nov,
  journal = {Journal of High Energy Physics},
  volume = {2016},
  number = {11},
  pages = {110},
  issn = {1029-8479},
  doi = {10.1007/JHEP11(2016)110},
  urldate = {2025-12-19},
  abstract = {Inclusive four-jet events produced in proton-proton collisions at a centre-of-mass energy of \$\$ \textbackslash sqrt\textbraceleft s\textbraceright =7 \$\$TeV are analysed for the presence of hard double-parton scattering using data corresponding to an integrated luminosity of 37.3 pb-1, collected with the ATLAS detector at the LHC. The contribution of hard double-parton scattering to the production of four-jet events is extracted using an artificial neural network, assuming that hard double-parton scattering can be approximated by an uncorrelated overlaying of dijet events. For events containing at least four jets with transverse momentum pT {$\geq$} 20 GeV and pseudorapidity \textbar{$\eta\vert$} {$\leq$} 4.4, and at least one having pT {$\geq$} 42.5 GeV, the contribution of hard double-parton scattering is estimated to be fDPS\,=\,0.092-\,0.011+\,0.005(stat.)-\,0.037+\,0.033(syst.). After combining this measurement with those of the inclusive dijet and four-jet cross-sections in the appropriate phase space regions, the effective cross-section, {$\sigma$}eff , was determined to be {$\sigma$}eff\,=\,14.\,9-\,1.0+\,1.2(stat.)-\,3.8+\,5.1(syst.) mb. This result is consistent within the quoted uncertainties with previous measurements of {$\sigma$}eff , performed at centre-of-mass energies between 63 GeV and 8 TeV using various final states, and it corresponds to 21-\,6+\,7\,\% of the total inelastic cross-section measured at \$\$ \textbackslash sqrt\textbraceleft s\textbraceright =7 \$\$TeV. The distributions of the observables sensitive to the contribution of hard double-parton scattering, corrected for detector effects, are also provided.},
  langid = {english},
  keywords = {Hadron-Hadron scattering (experiments)}
}

@article{aaboudStudyHardDoubleparton2019,
  title = {Study of the Hard Double-Parton Scattering Contribution to Inclusive Four-Lepton Production in Pp Collisions at s = 8 {{TeV}} with the {{ATLAS}} Detector},

  year = 2019,
  month = mar,
  journal = {Physics Letters B},
  volume = {790},
  pages = {595--614},
  issn = {03702693},
  doi = {10.1016/j.physletb.2019.01.062},
  urldate = {2025-12-19},
  langid = {english}
}

@article{aaijMeasurementPairProduction2017,
  title = {Measurement of the {{J}}/{$\psi$} Pair Production Cross-Section in Pp Collisions at \$\$ \textbackslash sqrt\textbraceleft s\textbraceright =13 \$\${{TeV}}},

  year = 2017,
  month = jun,
  journal = {Journal of High Energy Physics},
  volume = {2017},
  number = {6},
  pages = {47},
  issn = {1029-8479},
  doi = {10.1007/JHEP06(2017)047},
  urldate = {2025-12-19},
  abstract = {The production cross-section of J/{$\psi$} pairs is measured using a data sample of pp collisions collected by the LHCb experiment at a centre-of-mass energy of \$\$ \textbackslash sqrt\textbraceleft s\textbraceright =13 \$\$TeV, corresponding to an integrated luminosity of 279 \textpm 11 pb-1. The measurement is performed for J/{$\psi$} mesons with a transverse momentum of less than 10 GeV/c in the rapidity range 2.0 {$<$} y {$<$} 4.5. The production cross-section is measured to be 15.2 \textpm{} 1.0 \textpm{} 0.9 nb. The first uncertainty is statistical, and the second is systematic. The differential cross-sections as functions of several kinematic variables of the J/{$\psi$} pair are measured and compared to theoretical predictions.},
  langid = {english},
  keywords = {Hadron-Hadron scattering (experiments),Particle and resonance production,proton-proton scattering,QCD,Quarkonium}
}

@article{aaijObservationPsJPspair2012,
  title = {Observation of {{J}}/{$\psi<$}math{$><$}mi Mathvariant="normal" Is="true"{$>$}{{J}}{$<$}/Mi{$><$}mo Stretchy="false" Is="true"{$>$}/{$<$}/Mo{$><$}mo Is="true"{$>\psi<$}/Mo{$><$}/Math{$>$}-Pair Production in Pp Collisions at s={{7TeV}}{$<$}math{$><$}msqrt Is="true"{$><$}mi Is="true"{$>$}s{$<$}/Mi{$><$}/Msqrt{$><$}mo Is="true"{$>$}={$<$}/Mo{$><$}mn Is="true"{$>$}7{$<$}/Mn{$><$}mtext Is="true"{$>$} {{TeV}}{$<$}/Mtext{$><$}/Math{$>$}},

  year = 2012,
  month = jan,
  journal = {Physics Letters B},
  volume = {707},
  number = {1},
  pages = {52--59},
  issn = {0370-2693},
  doi = {10.1016/j.physletb.2011.12.015},
  urldate = {2025-12-19},
  abstract = {The production of J/{$\psi$} pairs in proton--proton collisions at a centre-of-mass energy of 7 TeV has been observed using an integrated luminosity of 37.5 pb-1 collected with the LHCb detector. The production cross-section for pairs with both J/{$\psi$} in the rapidity range 2},
  langid = {english}
}

@article{abazovObservationStudiesDouble2014,
  title = {Observation and Studies of Double {{J}} / {$\psi$} Production at the Tevatron},

  year = 2014,
  month = dec,
  journal = {Physical Review D},
  volume = {90},
  number = {11},
  pages = {111101},
  issn = {1550-7998, 1550-2368},
  doi = {10.1103/PhysRevD.90.111101},
  urldate = {2025-12-19},
  copyright = {http://link.aps.org/licenses/aps-default-license},
  langid = {english}
}

@article{abeStudyFourjetEvents1993,
  title = {Study of Four-Jet Events and Evidence for Double Parton Interactions in p p \textasciimacron{} Collisions at s = 1.8 {{TeV}}},

  year = 1993,
  month = jun,
  journal = {Physical Review D},
  volume = {47},
  number = {11},
  pages = {4857--4871},
  issn = {0556-2821},
  doi = {10.1103/PhysRevD.47.4857},
  urldate = {2026-01-12},
  copyright = {http://link.aps.org/licenses/aps-default-license},
  langid = {english},
  file = {/Users/ericwang/Zotero/storage/JKD4P65P/Abe 等 - 1993 - Study of four-jet events and evidence for double parton interactions in p p ¯ collisions at s = 1.8.pdf}
}

@article{akessonDoublePartonScattering1987,
  title = {Double Parton Scattering Inpp Collisions At\$\$\textbackslash sqrt s  = 63\$\${{GeV}}},

  year = 1987,
  month = jun,
  journal = {Zeitschrift f\"ur Physik C: Particles and Fields},
  volume = {34},
  number = {2},
  pages = {163--174},
  issn = {1431-5858},
  doi = {10.1007/BF01566757},
  urldate = {2025-12-19},
  abstract = {In a study ofpp collisions at\$\$\textbackslash sqrt s  = 63\$\$GeV with more than 29 GeV total transverse energy emitted into 1.8 units of rapidity in the central region, we have extracted a sample of 4-jet events and compared it with models of the two sources of 4-jet production: double bremsstrahlung and double parton scattering. The data cannot be described by bremsstrahlung alone, and we extract the fraction of 4-jet events attributed to double parton scattering for various definitions of the 4-jet sample. We determine the double parton scattering/2-jet yield ratio, and this leads to a determination of the proton radius. We discuss the implications of our observations for the general understanding of high-{$\Sigma$}ETevents.},
  langid = {english},
  keywords = {Central Region,Elementary Particle,Field Theory,Particle Acceleration,Quantum Field Theory},
  file = {/Users/ericwang/Zotero/storage/J7C3UJT2/Åkesson 等 - 1987 - Double parton scattering inpp collisions at$$sqrt s  = 63$$GeV.pdf}
}

@article{andersenExploringHighPurityMultiparton2024,
  title = {Exploring {{High-Purity Multiparton Scattering}} at {{Hadron Colliders}}},

  year = 2024,
  month = jan,
  journal = {Physical Review Letters},
  volume = {132},
  number = {4},
  pages = {041901},
  issn = {0031-9007, 1079-7114},
  doi = {10.1103/PhysRevLett.132.041901},
  urldate = {2026-01-12},
  abstract = {Multiparton interactions are a fascinating phenomenon that occur in almost every high-energy hadron-hadron collision yet are remarkably difficult to study quantitatively. In this Letter, we present a strategy to optimally disentangle multiparton interactions from the primary scattering in a collision. That strategy enables probes of multiparton interactions that are significantly beyond the state of the art, including their characteristic momentum scale, the interconnection between primary and secondary scatters, and the pattern of three and potentially even more simultaneous hard scatterings. This opens a path to powerful new constraints on multiparton interactions for LHC phenomenology and to the investigation of their rich field-theoretical structure.                                                                               Published by the American Physical Society                   2024},
  langid = {english},
  file = {/Users/ericwang/Zotero/storage/RSQSKNZF/Andersen 等 - 2024 - Exploring High-Purity Multiparton Scattering at Hadron Colliders.pdf}
}

@misc{araujoMeasurementPolarizationsPsi,
  title = {Measurement of the Polarizations of {{J}}/Psi and Psi({{2S}}) Mesons Promptly and Non-Promptly Produced in Pp Collisions at Sqrt(s) = 13 {{TeV}}},

  langid = {english},
  file = {/Users/ericwang/Zotero/storage/QD54MBES/Araujo 等 - Measurement of the polarizations of Jpsi and psi(2S) mesons promptly and non-promptly produced in p.pdf}
}

@article{atlascollaborationMeasurementDifferentialCrosssections2016,
  title = {Measurement of the Differential Cross-Sections of Prompt and Non-Prompt Production of \$\${{J}}/\textbackslash psi \$\$ {{J}} / {$\psi$} and \$\$\textbackslash psi (2\textbackslash mathrm \textbraceleft{{S}}\textbraceright )\$\$ {$\psi$} ( 2 {{S}} ) in Pp Collisions at \$\$\textbackslash sqrt\textbraceleft s\textbraceright{} = 7\$\$ s = 7 and 8 {{TeV}} with the {{ATLAS}} Detector},

  year = 2016,
  month = may,
  journal = {The European Physical Journal C},
  volume = {76},
  number = {5},
  pages = {283},
  issn = {1434-6044, 1434-6052},
  doi = {10.1140/epjc/s10052-016-4050-8},
  urldate = {2026-01-12},
  langid = {english},
  file = {/Users/ericwang/Zotero/storage/N4RW6YKA/ATLAS Collaboration 等 - 2016 - Measurement of the differential cross-sections of prompt and non-prompt production of $$Jpsi $$ J.pdf}
}

@article{atlascollaborationObservationDoubleParton2025,
  title = {Observation of Double Parton Scattering in Same-Sign {{W}} Boson Pair Production in Pp Collisions at \$\textbackslash sqrt\textbraceleft s\textbraceright =13\$ {{TeV}} with the {{ATLAS}} Detector},

  year = 2025,
  month = nov,
  journal = {Physics Letters B},
  volume = {870},
  eprint = {2505.08313},
  primaryclass = {hep-ex},
  pages = {139892},
  issn = {03702693},
  doi = {10.1016/j.physletb.2025.139892},
  urldate = {2026-01-12},
  abstract = {This letter reports the measurement of double parton scattering in same-sign W boson pair production with the ATLAS detector. The data set used corresponds to an integrated luminosity of 140 fb\$\textasciicircum\textbraceleft -1\textbraceright\$ of proton-proton collisions at a center-of-mass energy of 13 TeV, collected during Run 2 of the Large Hadron Collider. The study is performed in final states including two same-charge leptons, electron or muon, missing transverse momentum, and up to one jet. An excess of events is observed over the expected background contributions with a significance of 8.8 standard deviations. The measured fiducial cross section times leptonic branching fraction is \$4.59 \textbackslash pm 0.64\$ fb. The measurement corresponds to a double parton scattering effective cross section of \$10.6 \textbackslash pm 1.8\$ mb.},
  archiveprefix = {arXiv},
  langid = {english},
  keywords = {BETA,DPS,High Energy Physics - Experiment,Same-sign WW WW},
  file = {/Users/ericwang/Zotero/storage/8R8Q8IAA/Collaboration - 2025 - Observation of double parton scattering in same-sign W boson pair production in pp collisions at $s.pdf}
}

@book{bartaliniMultiplePartonInteractions2018,
  title = {Multiple Parton Interactions at the {{LHC}}},
  editor = {Bartalini, Paolo and Gaunt, Jonathan Richard},
  year = 2018,
  series = {Advanced Series on Directions in High Energy Physics},
  number = {vol. 29},
  publisher = {World Scientific},
  address = {New Jersey},
  abstract = {"Many high-energy collider experiments (including the current Large Hadron Collider at CERN) involve the collision of hadrons. Hadrons are composite particles consisting of partons (quarks and gluons), and this means that in any hadron-hadron collision there will typically be multiple collisions of the constituents -- i.e. multiple parton interactions (MPI). Understanding the nature of the MPI is important in terms of searching for new physics in the products of the scatters, and also in its own right to gain a greater understanding of hadron structure. This book aims at providing a pedagogical introduction and a comprehensive review of different research lines linked by an involvement of MPI phenomena. It is written by pioneers as well as young leading scientists, and reviews both experimental findings and theoretical developments, discussing also the remaining open issues"--},
  isbn = {978-981-322-775-0},
  langid = {english},
  lccn = {QC793.5.H328 M85 2018},
  keywords = {Hadron interactions,Partons,Scattering (Physics)}
}

@article{chatrchyanStudyDoubleParton2014,
  title = {Study of Double Parton Scattering Using {{W}} + 2-Jet Events in Proton-Proton Collisions at \$ \textbackslash sqrt\textbraceleft s\textbraceright{} \$= 7 {{TeV}}},

  year = 2014,
  month = mar,
  journal = {Journal of High Energy Physics},
  volume = {2014},
  number = {3},
  pages = {32},
  issn = {1029-8479},
  doi = {10.1007/JHEP03(2014)032},
  urldate = {2025-12-19},
  abstract = {Double parton scattering is investigated in proton-proton collisions at \$ \textbackslash sqrt\textbraceleft s\textbraceright{} \$= 7 TeV where the final state includes a W boson, which decays into a muon and a neutrino, and two jets. The data sample corresponds to an integrated luminosity of 5 fb-1, collected with the CMS detector at the LHC. Observables sensitive to double parton scattering are investigated after being corrected for detector effects and selection efficiencies. The fraction of W + 2-jet events due to double parton scattering is measured to be 0.055 \textpm{} 0.002 (stat.) \textpm{} 0.014 (syst.). The effective cross section, {$\sigma$}eff, characterizing the effective transverse area of hard partonic interactions in collisions between protons is measured to be 20.7 \textpm{} 0.8(stat.) \textpm{} 6.6(syst.)mb.},
  langid = {english},
  keywords = {Hadron-Hadron Scattering,Jet physics,QCD}
}

@article{cmscollaborationObservationSamesign$WW$2023,
  title = {Observation of Same-Sign \${{WW}}\$ Production from Double Parton Scattering in Proton-Proton Collisions at \$\textbackslash sqrt\textbraceleft s\textbraceright =13\textbackslash text\textbraceleft{} \textbraceright\textbackslash text\textbraceleft{} \textbraceright\textbackslash mathrm\textbraceleft{{TeV}}\textbraceright\$},

  year = 2023,
  month = sep,
  journal = {Physical Review Letters},
  volume = {131},
  number = {9},
  pages = {91803},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevLett.131.091803},
  urldate = {2026-01-02},
  abstract = {The first observation of the production of {$W\pm$}⁢{$W\pm$} bosons from double parton scattering processes using same-sign electron-muon and dimuon events in proton-proton collisions is reported. The data sample corresponds to an integrated luminosity of 138 fb-1 recorded at a center-of-mass energy of 13 TeV using the CMS detector at the CERN LHC. Multivariate discriminants are used to distinguish the signal process from the main backgrounds. A binned maximum likelihood fit is performed to extract the signal cross section. The measured cross section for production of same-sign {$W$} bosons decaying leptonically is 80.7\textpm 11.2⁢(stat)⁢ +9.5-8.6⁢(syst)\textpm 12.1⁢(model) fb, whereas the measured fiducial cross section is 6.28\textpm 0.81⁢(stat)\textpm 0.69⁢(syst)\textpm 0.37⁢(model) fb. The observed significance of the signal is 6.2 standard deviations above the background-only hypothesis.},
  langid = {english}
}

@article{collaborationMeasurement$JPs$pair2024,
  title = {Measurement of \${{J}}/{$\psi\$$}-Pair Production in \$pp\$ Collisions at \$\textbackslash sqrt\textbraceleft s\textbraceright =13\$ {{TeV}} and Study of Gluon Transverse-Momentum Dependent {{PDFs}}},

  year = 2024,
  month = mar,
  journal = {Journal of High Energy Physics},
  volume = {2024},
  number = {3},
  eprint = {2311.14085},
  primaryclass = {hep-ex},
  pages = {88},
  issn = {1029-8479},
  doi = {10.1007/JHEP03(2024)088},
  urldate = {2025-09-29},
  abstract = {The production cross-section of \$J/\textbackslash psi\$ pairs in proton-proton collisions at a centre-of-mass energy of \$\textbackslash sqrt\textbraceleft s\textbraceright =13\$ TeV is measured using a data sample corresponding to an integrated luminosity of 4.2 fb\$\textasciicircum\textbraceleft -1\textbraceright\$ collected by the LHCb experiment. The measurement is performed with both \$J/\textbackslash psi\$ mesons in the transverse momentum range \$0},
  archiveprefix = {arXiv},
  langid = {english},
  keywords = {High Energy Physics - Experiment},
  file = {/Users/ericwang/Zotero/storage/G9IWJQB2/collaboration 等 - 2024 - Measurement of $Jψ$-pair production in $pp$ collisions at $sqrt s =13$ TeV and study of gluon tran.pdf}
}

@article{collaborationMeasurementAssociated$J2024,
  title = {Measurement of Associated \${{J}}/{$\psi\$$}-\${$\psi$}({{2S}})\$ Production Cross-Section in \$pp\$ Collisions at \$\textbackslash sqrt\textbraceleft s\textbraceright =13\$ {{TeV}}},

  year = 2024,
  month = may,
  journal = {Journal of High Energy Physics},
  volume = {2024},
  number = {5},
  eprint = {2311.15921},
  primaryclass = {hep-ex},
  pages = {259},
  issn = {1029-8479},
  doi = {10.1007/JHEP05(2024)259},
  urldate = {2025-09-29},
  abstract = {The cross-section of associated \$J/\textbackslash psi\$-\$\textbackslash psi(2S)\$ production in proton-proton collisions at a centre-of-mass energy of \$\textbackslash sqrt\textbraceleft s\textbraceright =13\$ TeV is measured using a data sample corresponding to an integrated luminosity of 4.2 fb\$\textasciicircum\textbraceleft -1\textbraceright\$, collected by the LHCb experiment. The measurement is performed for both \$J/\textbackslash psi\$ and \$\textbackslash psi(2S)\$ mesons having transverse momentum \$p\_\textbraceleft\textbackslash text\textbraceleft T\textbraceright\textbraceright{$<$}14\$ GeV/\$c\$ and rapidity \$2.0},
  archiveprefix = {arXiv},
  langid = {english},
  keywords = {High Energy Physics - Experiment},
  file = {/Users/ericwang/Zotero/storage/FKZG8ZEJ/collaboration 等 - 2024 - Measurement of associated $Jψ$-$ψ(2S)$ production cross-section in $pp$ collisions at $sqrt s =13$.pdf}
}

@article{collaborationObservationWZ$g$Production2025,
  title = {Observation of {{WZ}}\${$\gamma\$$} Production and Constraints on New Physics Scenarios in Proton-Proton Collisions at \$\textbackslash sqrt\textbraceleft s\textbraceright\$ = 13 {{TeV}}},

  year = 2025,
  month = jul,
  journal = {Physical Review D},
  volume = {112},
  number = {1},
  eprint = {2503.21977},
  primaryclass = {hep-ex},
  pages = {012009},
  issn = {2470-0010, 2470-0029},
  doi = {10.1103/cm24-665b},
  urldate = {2025-09-29},
  abstract = {A measurement of the WZ\$\textbackslash gamma\$ triboson production cross section is presented. The analysis is based on a data sample of proton-proton collisions at a center-of-mass energy of \$\textbackslash sqrt\textbraceleft s\textbraceright\$ = 13 TeV recorded with the CMS detector at the LHC, corresponding to an integrated luminosity of 138 fb\$\textasciicircum\textbraceleft -1\textbraceright\$. The analysis focuses on the final state with three charged leptons, \$\textbackslash ell\textasciicircum\textbackslash pm\textbackslash nu\textbackslash ell\textasciicircum +\textbackslash ell\textasciicircum -\$, where \$\textbackslash ell\$ = e or \$\textbackslash mu\$, accompanied by an additional photon. The observed (expected) significance of the WZ\$\textbackslash gamma\$ signal is 5.4 (3.8) standard deviations. The cross section is measured in a fiducial region, where events with an \$\textbackslash ell\$ originating from a tau lepton decay are excluded, to be 5.48 \$\textbackslash pm\$ 1.11 fb, which is compatible with the prediction of 3.69 \$\textbackslash pm\$ 0.24 fb at next-to-leading order in quantum chromodynamics. Exclusion limits are set on anomalous quartic gauge couplings and on the production cross sections of massive axion-like particles.},
  archiveprefix = {arXiv},
  langid = {english},
  keywords = {High Energy Physics - Experiment},
  file = {/Users/ericwang/Zotero/storage/5AK4KGPZ/Collaboration - 2025 - Observation of WZ$γ$ production and constraints on new physics scenarios in proton-proton collisions.pdf}
}

@incollection{d?enterriaDoubleTripleNparton2017,
  title = {Double, Triple, and n-Parton Scatterings in High-Energy Proton and Nuclear Collisions},
  booktitle = {Multiple Parton Interactions at the {{LHC}}},

  year = 2017,
  month = may,
  series = {Advanced {{Series}} on {{Directions}} in {{High Energy Physics}}},
  volume = {Volume 29},
  pages = {159--187},
  publisher = {WORLD SCIENTIFIC},
  doi = {10.1142/9789813227767_0009},
  urldate = {2025-12-19},
  isbn = {978-981-322-775-0},
  langid = {english}
}

@article{d0collaborationEvidenceSimultaneousProduction2016,
  title = {Evidence for Simultaneous Production of \${{J}}/\textbackslash ensuremath\textbraceleft\textbackslash psi\textbraceright\$ and \$\textbackslash mathrm\textbraceleft\textbackslash ensuremath\textbraceleft\textbackslash upsilon\textbraceright\textbraceright\$ Mesons},

  year = 2016,
  month = feb,
  journal = {Physical Review Letters},
  volume = {116},
  number = {8},
  pages = {82002},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevLett.116.082002},
  urldate = {2025-12-19},
  abstract = {We report evidence for the simultaneous production of {$J$}/{$\psi$} and {$\Upsilon$} mesons in 8.1 fb-1 of data collected at \textsurd{$s$} =1.96 TeV by the D0 experiment at the Fermilab {$p$}⁢\textasciimacron{$p$} Tevatron Collider. Events with these characteristics are expected to be produced predominantly by gluon-gluon interactions. In this analysis, we extract the effective cross section characterizing the initial parton spatial distribution, {$\sigma$}eff=2.2\textpm 0.7⁢(stat)\textpm 0.9⁢(syst) ⁢mb.}
}

@article{denterriaTriplePartonScatterings2017,
  title = {Triple {{Parton Scatterings}} in {{High-Energy Proton-Proton Collisions}}},

  year = 2017,
  month = mar,
  journal = {Physical Review Letters},
  volume = {118},
  number = {12},
  pages = {122001},
  issn = {0031-9007, 1079-7114},
  doi = {10.1103/PhysRevLett.118.122001},
  urldate = {2025-09-29},
  copyright = {https://creativecommons.org/licenses/by/4.0/},
  langid = {english},
  file = {/Users/ericwang/Zotero/storage/82PG9EUK/d’Enterria和Snigirev - 2017 - Triple Parton Scatterings in High-Energy Proton-Proton Collisions.pdf}
}

@article{denterriaTriplePartonScatterings2017a,
  title = {Triple Parton Scatterings in High-Energy Proton-Proton Collisions},

  year = 2017,
  month = mar,
  journal = {Physical Review Letters},
  volume = {118},
  number = {12},
  pages = {122001},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevLett.118.122001},
  urldate = {2025-12-19},
  abstract = {A generic expression to compute triple parton scattering cross sections in high-energy proton-proton ({$p$}⁢{$p$}) collisions is presented as a function of the corresponding single parton cross sections and the transverse parton profile of the proton encoded in an effective parameter {$\sigma$}eff,TPS. The value of {$\sigma$}eff,TPS is closely related to the similar effective cross section that characterizes double parton scatterings, and amounts to {$\sigma$}eff,TPS=12.5\textpm 4.5 mb. Estimates for triple charm ({$c$}⁢\textasciimacron{$c$}) and bottom ({$b$}⁢\textasciimacron{$b$}) production in {$p$}⁢{$p$} collisions at LHC and FCC energies are presented based on next-to-next-to-leading-order perturbative calculations for single {$c$}⁢\textasciimacron{$c$}, {$b$}⁢\textasciimacron{$b$} cross sections. At \textsurd{$s$} {$\approx$}100 TeV, about 15\% of the {$p$}⁢{$p$} collisions produce three {$c$}⁢\textasciimacron{$c$} pairs from three different parton-parton scatterings.},
  langid = {english}
}

@article{diehlElementsTheoryMultiparton2012,
  title = {Elements of a Theory for Multiparton Interactions in {{QCD}}},

  year = 2012,
  month = mar,
  journal = {Journal of High Energy Physics},
  volume = {2012},
  number = {3},
  pages = {89},
  issn = {1029-8479},
  doi = {10.1007/JHEP03(2012)089},
  urldate = {2025-09-29},
  abstract = {We perform a detailed investigation of multiple hard interactions in hadronhadron collisions. We discuss the space-time, spin and color structure of multiple interactions, classify different contributions according to their power behavior and provide several elements required for establishing all-order factorization. This also allows us to analyze the structure of Sudakov logarithms in double hard scattering. We show how multiparton distributions can be constrained by connecting them with generalized parton distributions and by calculating their behavior at large transverse parton momenta.},
  langid = {english},
  file = {/Users/ericwang/Zotero/storage/RQIE2XBX/Diehl 等 - 2012 - Elements of a theory for multiparton interactions in QCD.pdf}
}

@misc{hadleyObservationMeasurementsProduction,
  title = {Observation and Measurements of the Production of {{Upsilon}}({{1S}}) Mesons in Association with {{Z}} Bosons in Proton-Proton Collisions at Sqrt(s)=13 {{TeV}}},

  langid = {english},
  file = {/Users/ericwang/Zotero/storage/A95WQ7IB/Hadley和Leontsinis - Observation and measurements of the production of Upsilon(1S) mesons in association with Z bosons in.pdf}
}

@article{khachatryanMeasurementPromptPair2014,
  title = {Measurement of Prompt {{J}}/{$\psi$} Pair Production in Pp Collisions at \$\$ \textbackslash sqrt\textbraceleft s\textbraceright{} \$\$= 7 Tev},

  year = 2014,
  month = sep,
  journal = {Journal of High Energy Physics},
  volume = {2014},
  number = {9},
  pages = {94},
  issn = {1029-8479},
  doi = {10.1007/JHEP09(2014)094},
  urldate = {2025-12-19},
  abstract = {Production of prompt J/{$\psi$} meson pairs in proton-proton collisions at \$\$ \textbackslash sqrt\textbraceleft s\textbraceright{} \$\$= 7 TeV is measured with the CMS experiment at the LHC in a data sample corresponding to an integrated luminosity of about 4.7 fb-1. The two J/{$\psi$} mesons are fully reconstructed via their decays into {$\mu$}+{$\mu-$}pairs. This observation provides for the first time access to the high-transverse-momentum region of J/{$\psi$} pair production where model predictions are not yet established. The total and differential cross sections are measured in a phase space defined by the individual J/{$\psi$} transverse momentum (pTJ/{$\psi$}) and rapidity (\textbar yJ/{$\psi\vert$}): \textbar yJ/{$\psi\vert$} {$<$} 1.2 for pTJ/{$\psi>$} 6.5 GeV/c; 1.2 {$<$} \textbar yJ/{$\psi\vert$} {$<$} 1.43 for a pT threshold that scales linearly with \textbar yJ/{$\psi\vert$} from 6.5 to 4.5 GeV/c; and 1.43 {$<$} \textbar yJ/{$\psi\vert$} {$<$} 2.2 for pTJ/{$\psi>$} 4.5 GeV/c. The total cross section, assuming unpolarized prompt J/{$\psi$} pair production is 1.49 \textpm{} 0.07 (stat) \textpm 0.13 (syst) nb. Different assumptions about the J/{$\psi$} polarization imply modifications to the cross section ranging from -31\% to +27\%.},
  langid = {english},
  keywords = {B physics,Hadron-Hadron Scattering}
}

@article{khachatryanObservationY1SPair2017,
  title = {Observation of {{Y}}({{1S}}) Pair Production in Proton-Proton Collisions at \$\$ \textbackslash sqrt\textbraceleft s\textbraceright =8 \$\${{TeV}}},

  year = 2017,
  month = may,
  journal = {Journal of High Energy Physics},
  volume = {2017},
  number = {5},
  pages = {13},
  issn = {1029-8479},
  doi = {10.1007/JHEP05(2017)013},
  urldate = {2025-12-19},
  abstract = {Pair production of Y(1S) mesons is observed at the LHC in proton-proton collisions at \$\$ \textbackslash sqrt\textbraceleft s\textbraceright =8 \$\$TeV by the CMS experiment in a data sample corresponding to an integrated luminosity of 20.7 fb-1. Both Y(1S) candidates are fully reconstructed via their decays to {$\mu$}+{$\mu-$}. The fiducial acceptance region is defined by an absolute Y(1S) rapidity smaller than 2.0. The fiducial cross section for the production of Y(1S) pairs, assuming that both mesons decay isotropically, is measured to be 68.8\textpm 12.7 (stat)\textpm 7.4 (syst)\textpm 2.8 (\$\$ \textbackslash mathrm\textbraceleft\textbackslash mathcal\textbraceleft B\textbraceright\textbraceright{} \$\$) pb, where the third uncertainty comes from the uncertainty in the branching fraction of Y(1S) decays to {$\mu$}+{$\mu-$}. Assuming instead that the Y(1S) mesons are produced with different polarizations leads to variations in the measured cross section in the range from -38\% to +36\%.},
  langid = {english},
  keywords = {Hadron-Hadron scattering (experiments),Quarkonium}
}

@misc{leontsinisObservationTriplePsi,
  title = {Observation of Triple {{J}}/Psi Meson Production in Proton-Proton Collisions at 13 {{TeV}}},

  langid = {english},
  file = {/Users/ericwang/Zotero/storage/WGHDGJYM/Leontsinis - Observation of triple Jpsi meson production in proton-proton collisions at 13 TeV.pdf}
}

@misc{PromptPsiPair,
  title = {Prompt {{J}}/Psi Pair Differential Cross Section in Pp Collisions at Sqrts=13 {{TeV}} with the {{CMS}} Experiment},
  langid = {english},
  file = {/Users/ericwang/Zotero/storage/56J9CVPG/Prompt Jpsi pair differential cross section in pp collisions at sqrts=13 TeV with the CMS experimen.pdf}
}

@article{shaoTriplePrompt$J2019,
  title = {Triple Prompt \${{J}}/\textbackslash ensuremath\textbraceleft\textbackslash psi\textbraceright\$ Hadroproduction as a Hard Probe of Multiple-Parton Scatterings},

  year = 2019,
  month = may,
  journal = {Physical Review Letters},
  volume = {122},
  number = {19},
  pages = {192002},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevLett.122.192002},
  urldate = {2025-11-13},
  abstract = {We propose that the process of triple prompt {$J$}/{$\psi$} hadroproduction is a very clean hard probe of multiple-parton scatterings at high-energy hadron colliders, especially the least known triple-parton scattering. A first complete study is carried out by considering single-, double-, and triple-parton scatterings coherently. Our calculation shows that it is a golden channel to probe double- and triple-parton scatterings, as the single-parton scattering is strongly suppressed. The predictions of the (differential) cross sections in proton-proton collisions at the LHC and future higher-energy hadron colliders are given. Our study shows that its measurement is already feasible with the existing data collected during the period of the LHC run 2. A method is proposed to extract the triple-parton scattering contribution, and therefore it paves a way to study the possible triple-parton correlations in a proton.我们提出，三重提示 {$J$}/{$\psi$} 强子产生过程是高能强子对撞机上多重子散射的一个非常干净的硬探针，特别是最少为人知的三重子散射。我们通过考虑单重、双重和三重子散射协同地进行了首次完整研究。我们的计算表明，由于单重子散射受到强烈抑制，这是探测双重和三重子散射的黄金通道。给出了在 LHC 和未来更高能量强子对撞机上质子-质子碰撞的（微分）截面预测。我们的研究表明，其测量在 LHC 运行 2 期间收集的现有数据中已经可以实现。我们提出了一种提取三重子散射贡献的方法，因此为研究质子中可能的三重子关联铺平了道路。},
  langid = {english},
  file = {/Users/ericwang/Zotero/storage/PQVPGJK9/Shao和Zhang - 2019 - Triple Prompt J  ψ Hadroproduction as a Hard Probe of Multiple-Parton Scatterings.pdf}
}

@article{sirunyanConstraintsDoublepartonScattering2018,
  title = {Constraints on the Double-Parton Scattering Cross Section from Same-Sign {{W}} Boson Pair Production in Proton-Proton Collisions at \$\$ \textbackslash sqrt\textbraceleft s\textbraceright =8 \$\${{TeV}}},

  year = 2018,
  month = feb,
  journal = {Journal of High Energy Physics},
  volume = {2018},
  number = {2},
  pages = {32},
  issn = {1029-8479},
  doi = {10.1007/JHEP02(2018)032},
  urldate = {2025-12-19},
  abstract = {A first search for same-sign WW production via double-parton scattering is performed based on proton-proton collision data at a center-of-mass energy of 8 TeV using dimuon and electron-muon final states. The search is based on the analysis of data corresponding to an integrated luminosity of 19.7 fb-1. No significant excess of events is observed above the expected single-parton scattering yields. A 95\% confidence level upper limit of 0.32 pb is set on the inclusive cross section for same-sign WW production via the double-parton scattering process. This upper limit is used to place a 95\% confidence level lower limit of 12.2 mb on the effective double-parton cross section parameter, closely related to the transverse distribution of partons in the proton. This limit on the effective cross section is consistent with previous measurements as well as with Monte Carlo event generator predictions.},
  langid = {english},
  keywords = {Hadron-Hadron scattering (experiments)}
}

@article{sirunyanMeasurementY1SPair2020,
  title = {Measurement of the {{Y}}({{1S}}) Pair Production Cross Section and Search for Resonances Decaying to {{Y}}({{1S}}){$\mu$}+{$\mu$}- in Proton-Proton Collisions at s={{13TeV}}{$<$}math{$><$}msqrt Is="true"{$><$}mrow Is="true"{$><$}mi Is="true"{$>$}s{$<$}/Mi{$><$}/Mrow{$><$}/Msqrt{$><$}mo Linebreak="goodbreak" Linebreakstyle="after" Is="true"{$>$}={$<$}/Mo{$><$}mn Is="true"{$>$}13{$<$}/Mn{$><$}mspace Width="0.25em" Is="true"{$><$}/Mspace{$><$}mtext Is="true"{$>$}{{TeV}}{$<$}/Mtext{$><$}/Math{$>$}},

  year = 2020,
  month = sep,
  journal = {Physics Letters B},
  volume = {808},
  pages = {135578},
  issn = {0370-2693},
  doi = {10.1016/j.physletb.2020.135578},
  urldate = {2025-12-19},
  abstract = {The fiducial cross section for Y(1S) pair production in proton-proton collisions at a center-of-mass energy of 13 TeV in the region where both Y(1S) mesons have an absolute rapidity below 2.0 is measured to be 79\textpm 11(stat)\textpm 6(syst)\textpm 3(B)pb assuming the mesons are produced unpolarized. The last uncertainty corresponds to the uncertainty in the Y(1S) meson dimuon branching fraction. The measurement is performed in the final state with four muons using proton-proton collision data collected in 2016 by the CMS experiment at the LHC, corresponding to an integrated luminosity of 35.9fb-1. This process serves as a standard model reference in a search for narrow resonances decaying to Y(1S){$\mu$}+{$\mu-$} in the same final state. Such a resonance could indicate the existence of a tetraquark that is a bound state of two b quarks and two b\textasciimacron{} antiquarks. The tetraquark search is performed for masses in the vicinity of four times the bottom quark mass, between 17.5 and 19.5 GeV, while a generic search for other resonances is performed for masses between 16.5 and 27 GeV. No significant excess of events compatible with a narrow resonance is observed in the data. Limits on the production cross section times branching fraction to four muons via an intermediate Y(1S) resonance are set as a function of the resonance mass.},
  langid = {english},
  keywords = {CMS,Upsilon}
}

@article{sjostrandMultipleinteractionModelEvent1987,
  title = {A Multiple-Interaction Model for the Event Structure in Hadron Collisions},

  year = 1987,
  month = oct,
  journal = {Physical Review D},
  volume = {36},
  number = {7},
  pages = {2019--2041},
  issn = {0556-2821},
  doi = {10.1103/PhysRevD.36.2019},
  urldate = {2025-09-29},
  copyright = {http://link.aps.org/licenses/aps-default-license},
  langid = {english},
  file = {/Users/ericwang/Zotero/storage/UZ2VEBS7/Sjöstrand和Van Zijl - 1987 - A multiple-interaction model for the event structure in hadron collisions.pdf}
}

@article{theatlascollaborationMeasurementHardDoubleparton2013,
  title = {Measurement of Hard Double-Parton Interactions in {{{\emph{W}}}} ({$\rightarrow\ell$} {\emph{{$\nu$}}} ) + 2-Jet Events at \$\textbackslash sqrt\textbraceleft s\textbraceright\textbackslash,=7\$ {{TeV}} with the {{ATLAS}} Detector},

  year = 2013,
  month = mar,
  journal = {New Journal of Physics},
  volume = {15},
  number = {3},
  pages = {33038},
  issn = {1367-2630},
  doi = {10.1088/1367-2630/15/3/033038},
  urldate = {2025-12-19},
  copyright = {http://iopscience.iop.org/info/page/text-and-data-mining},
  langid = {english}
}

@article{thecmscollaborationObservationTripleMeson2023,
  title = {Observation of Triple {{J}}/{$\psi$} Meson Production in Proton-Proton Collisions},

  year = 2023,
  month = mar,
  journal = {Nature Physics},
  volume = {19},
  number = {3},
  pages = {338--350},
  issn = {1745-2473, 1745-2481},
  doi = {10.1038/s41567-022-01838-y},
  urldate = {2025-01-09},
  abstract = {Abstract                            Protons consist of three valence quarks, two up-quarks and one down-quark, held together by gluons and a sea of quark-antiquark pairs. Collectively, quarks and gluons are referred to as partons. In a proton-proton collision, typically only one parton of each proton undergoes a hard scattering -- referred to as single-parton scattering -- leaving the remainder of each proton only slightly disturbed. Here, we report the study of double- and triple-parton scatterings through the simultaneous production of three J/               {$\psi$}               mesons, which consist of a charm quark-antiquark pair, in proton-proton collisions recorded with the CMS experiment at the Large Hadron Collider. We observed this process -- reconstructed through the decays of J/               {$\psi$}               mesons into pairs of oppositely charged muons -- with a statistical significance above five standard deviations. We measured the inclusive fiducial cross-section to be                                                   \$\$27\textbraceleft 2\textbraceright\_\textbraceleft -104\textbraceright\textasciicircum\textbraceleft +141\textbraceright\textbackslash,\textbraceleft\textbraceleft\textbraceleft\textbackslash rm\textbraceleft (stat)\textbraceright\textbraceright\textbraceright\textbraceright\textbackslash,\textbackslash pm 17\textbackslash,\textbraceleft\textbraceleft\textbraceleft\textbackslash rm\textbraceleft (syst)\textbraceright\textbraceright\textbraceright\textbraceright\textbackslash,\textbraceleft\textbraceleft\textbraceleft\textbackslash rm\textbraceleft fb\textbraceright\textbraceright\textbraceright\textbraceright\textbackslash,\$\$                                                               27                                                                           2                                                                             -                           104                                                                             +                           141                                                                                              (stat)                                              \textpm{}                       17                                              (syst)                                              fb                                                                                       , and compared it to theoretical expectations for triple-J/               {$\psi$}               meson production in single-, double- and triple-parton scattering scenarios. Assuming factorization of multiple hard-scattering probabilities in terms of single-parton scattering cross-sections, double- and triple-parton scattering are the dominant contributions for the measured process.},
  langid = {english},
  file = {/Users/ericwang/Zotero/storage/B8DSWING/The CMS Collaboration 等 - 2023 - Observation of triple Jψ meson production in proton-proton collisions.pdf}
}

@article{thecmscollaborationPromptNonpromptProduction2011,
  title = {Prompt and Non-Prompt {{J}}/{$\psi$} Production in Pp Collisions at \$\textbackslash sqrt\textbraceleft s\textbraceright{} = 7\$ {{TeV}}},

  year = 2011,
  month = mar,
  journal = {The European Physical Journal C},
  volume = {71},
  number = {3},
  pages = {1575},
  issn = {1434-6044, 1434-6052},
  doi = {10.1140/epjc/s10052-011-1575-8},
  urldate = {2026-01-12},
  langid = {english},
  file = {/Users/ericwang/Zotero/storage/HHQLGEER/The CMS Collaboration 等 - 2011 - Prompt and non-prompt Jψ production in pp collisions at $sqrt s = 7$ TeV.pdf}
}

@article{tumasyanMeasurementDoublepartonScattering2022,
  title = {Measurement of Double-Parton Scattering in Inclusive Production of Four Jets with Low Transverse Momentum in Proton-Proton Collisions at \$\$ \textbackslash sqrt\textbraceleft s\textbraceright{} \$\$= 13 {{TeV}}},

  year = 2022,
  month = jan,
  journal = {Journal of High Energy Physics},
  volume = {2022},
  number = {1},
  pages = {177},
  issn = {1029-8479},
  doi = {10.1007/JHEP01(2022)177},
  urldate = {2025-12-19},
  abstract = {A measurement of inclusive four-jet production in proton-proton collisions at a center-of-mass energy of 13 TeV is presented. The transverse momenta of jets within \textbar{$\eta\vert$} {$<$} 4.7 are required to exceed 35, 30, 25, and 20 GeV for the first-, second-, third-, and fourth-leading jet, respectively. Differential cross sections are measured as functions of the jet transverse momentum, jet pseudorapidity, and several other observables that describe the angular correlations between the jets. The measured distributions show sensitivity to different aspects of the underlying event, parton shower modeling, and matrix element calculations. In particular, the interplay between angular correlations caused by parton shower and double-parton scattering contributions is shown to be important. The double-parton scattering contribution is extracted by means of a template fit to the data, using distributions for single-parton scattering obtained from Monte Carlo event generators and a double-parton scattering distribution constructed from inclusive single-jet events in data. The effective double-parton scattering cross section is calculated and discussed in view of previous measurements and of its dependence on the models used to describe the single- parton scattering background.},
  langid = {english},
  keywords = {Hadron-Hadron Scattering,Jets,QCD}
}

@techreport{zhangTriplePromptHadroproduction2021,
  title = {Triple Prompt {{J}}/{$\psi$} Hadroproduction and Multiple-Parton Interaction},

  year = 2021,
  month = nov,
  address = {Beijing},
  institution = {Peking University},
  langid = {english},
  file = {/Users/ericwang/Zotero/storage/E9TAEFPK/Zhang - Triple prompt Jψ hadroproduction and multiple-parton interaction.pdf}
}

```
Gemini response:

```tex
Of course. It is a pleasure to assist you with your bachelor thesis review. Structuring existing knowledge is a crucial skill in research, and a well-organized literature review is the foundation of a strong thesis.

Based on the provided document structure and the list of experimental and theoretical studies, I have produced a draft that expands upon your initial text. This draft integrates the references you provided into a continuous narrative, following the formatting and style of your LaTeX document. The goal is to create a more detailed and referenced account of the field, which you can then refine and build upon.

I have focused on enriching the `Introduction` section, as this is where a comprehensive review of the field is most appropriate. The text aims to logically connect the pioneering studies to the current state-of-the-art, highlighting the key questions and how they lead to your specific research topic.

Here is the draft in LaTeX code format.

```latex
\documentclass[10pt,twocolumn,draft]{article} 
\usepackage{simpleConference}
\usepackage{fancyhdr}
\usepackage{amsmath,amsfonts,amssymb,graphicx}
\usepackage{subfigure}   % 使用子图形
\usepackage{indentfirst} % 中文段落首行缩进
\usepackage{bm}          % 公式中的粗体字符(用命令\boldsymbol）
\usepackage{indentfirst} % 中文首段缩进
\usepackage{abstract}    % 2栏文档，一栏摘要及关键字宏包
\usepackage{amsthm}      % 使用定理
\usepackage{booktabs}    % 使用表格
\usepackage{siunitx}
\usepackage{tikz}
\usepackage{enumitem}
\usepackage{titlesec}
\usepackage{times}
\usepackage{wasysym}
\usepackage{pifont}
\usepackage{ccaption}
\usepackage{float}
\usepackage{calc}
\usetikzlibrary{calc}
\usetikzlibrary{circuits.ee.IEC}
% 在导言区添加 circuitikz 包
\usepackage{circuitikz}
\usepackage{environ}
\usepackage{lmodern}
\usepackage{anyfontsize}
\usepackage{hyperref}
\usepackage{tabu}
\usepackage{tabularx}
\usepackage{multirow}
\usepackage{multicol}
\usepackage{longtable}
\usepackage{makecell}
\usepackage{graphicx}
\usepackage{amssymb}
\usepackage{ragged2e}
\usepackage{url,hyperref}

\newcommand*{\effXsecDPS}{\sigma_{\text{eff,DPS}}}
\newcommand*{\effXsecTPS}{\sigma_{\text{eff,TPS}}}
\newcommand*{\GeV}{~\text{GeV}}
\newcommand*{\GeVc}{~\text{GeV/c}}
\newcommand*{\GeVcs}{~\text{GeV}\text{c}^2}

\renewcommand{\arraystretch}{1.2}

\begin{document}

% Multi-Parton Scattering in High-Energy Proton-Proton Collisions

\title{}

\author{Chi Wang \\
Zhili College, Tsinghua University, China \\
\today
\\
\\
chi.w@cern.ch  \\
}

\maketitle
\thispagestyle{empty}

\begin{abstract}

\end{abstract}


\section{Introduction}

\subsection{Multi-Parton Scattering in Proton-Proton Collisions}

The proton, while simple in its valence quark composition of two up-type and one down-type quarks, possesses a rich and complex internal structure. This structure is composed of not only the valence quarks but also the gluons that bind them and a dynamic 'sea' of virtual quark-antiquark pairs. In the framework of high-energy physics, these constituents are collectively referred to as 'partons'. In the traditional picture of proton-proton ($pp$) collisions, a single hard scattering occurs between one parton from each proton, with the remaining partons, or 'spectators', being only peripherally involved. However, as the center-of-mass energy of the collision increases, the probed partons, particularly gluons and sea quarks at low momentum fractions, grow in density. This increased density enhances the probability of multiple pairs of partons undergoing simultaneous hard scatterings within a single $pp$ event. Such phenomena are collectively known as multi-parton scattering (MPS) \cite{sjostrandMultipleinteractionModelEvent1987}.

MPS processes are of profound interest for two primary reasons. Firstly, they serve as a unique and powerful probe into the three-dimensional structure of the proton. The study of MPS provides access to the correlations between partons in position, momentum, flavor, and spin, offering insights that are complementary to the one-dimensional information provided by standard parton distribution functions \cite{diehlElementsTheoryMultiparton2012, bartaliniMultiplePartonInteractions2018}. These correlations are governed by non-perturbative Quantum Chromodynamics (QCD) and are thus challenging to calculate from first principles, making experimental investigation indispensable. Secondly, MPS constitutes a significant and often irreducible background to many Standard Model precision measurements and searches for new physics. Complex final states with multiple jets, leptons, or bosons can be mimicked by MPS events, and a precise understanding of their contribution is crucial for future discoveries, especially at the high-luminosity frontiers of current and future hadron colliders \cite{denterriaTriplePartonScatterings2017a, andersenExploringHighPurityMultiparton2024}.

\subsection{The "Pocket Formula" and \texorpdfstring{$\sigma_{\text{eff}}$}{Effective Cross-Section}}

The simplest theoretical treatment of MPS assumes that the individual parton-parton scatterings are uncorrelated. Under this assumption, the cross-section for an n-parton scattering (NPS) process producing final states $\psi_1, \dots, \psi_n$ can be related to the cross-sections of the corresponding single-parton scattering (SPS) processes through the so-called "pocket formula":
\begin{equation}
\begin{aligned}
    \label{eqn:nps_pocket}
    \sigma^{pp\to\psi_1+\cdots+\psi_n+X}_{\text{NPS}} =
    \left(\frac {\mathfrak{m}}{n!}\right) \frac{\prod_{i=1}^{n}\sigma_{\text{SPS}}^{pp\to \psi_i+X}}{(\sigma_{\text{eff,NPS}})^{n-1}}
\end{aligned}
\end{equation}
Here, $\mathfrak{m}$ is a combinatorial factor for identical final states, and $\sigma_{\text{eff,NPS}}$ is the effective cross-section. This crucial parameter, $\sigma_{\text{eff}}$, quantifies the transverse overlap of the interacting partons and is inversely related to the spatial density of partons within the proton. A smaller $\sigma_{\text{eff}}$ implies a more concentrated parton distribution.

Double parton scattering (DPS), the $n=2$ case, is the most frequently studied MPS process. The first experimental evidence for DPS was reported by the AFS collaboration at the ISR in four-jet final states \cite{akessonDoublePartonScattering1987}, with further confirmation from the CDF experiment at the Tevatron \cite{abeStudyFourjetEvents1993}. Since these pioneering measurements, DPS has been extensively studied at the LHC, revealing a puzzling pattern. Measurements in final states containing jets and/or electroweak bosons, such as 4-jet by ATLAS \cite{aaboudStudyHardDoubleparton2016} and CMS \cite{tumasyanMeasurementDoublepartonScattering2022}, and W+2-jet by ATLAS \cite{theatlascollaborationMeasurementHardDoubleparton2013} and CMS \cite{chatrchyanStudyDoubleParton2014}, consistently yield a value of $\effXsecDPS \approx 10-20~\text{mb}$. This range has been further corroborated by recent clean measurements of same-sign W boson pair production from both the CMS \cite{cmscollaborationObservationSamesign$WW$2023} and ATLAS \cite{atlascollaborationObservationDoubleParton2025} collaborations.

In stark contrast, measurements involving the production of heavy quarkonia show a significantly different result. Studies of di-$J/\psi$ production by the D0 \cite{abazovObservationStudiesDouble2014}, LHCb \cite{aaijObservationPsJPspair2012, aaijMeasurementPairProduction2017}, ATLAS \cite{aaboudMeasurementPrompt$$psi2017}, and CMS \cite{khachatryanMeasurementPromptPair2014} collaborations, as well as di-$\Upsilon$ production by CMS \cite{khachatryanObservationY1SPair2017, sirunyanMeasurementY1SPair2020}, consistently extract a much smaller effective cross-section, with $\effXsecDPS \approx 3-10~\text{mb}$. This discrepancy challenges the simple assumption of a universal $\sigma_{\text{eff}}$ and is often interpreted as evidence that different final states probe partons (e.g., gluons versus quarks) with different transverse spatial distributions within the proton. This tension highlights the need for further independent probes of the proton's internal structure, such as those offered by triple parton scattering.

% The figure below was in your original document. I have commented it out as I cannot generate the image file.
% \begin{figure}[!htbp]
%     \centering
%     \includegraphics[width=1.0\linewidth]{images/sigma_eff_DPS_summary.png}
%     \caption{Summary of current \texorpdfstring{$\effXsecDPS$}{DPS effective cross-section} measurement results in various final states, including results from the triple-$J/\psi$ production process on the top.\cite{CMS_TRI_JPSI}}
%     \label{fig:sigma-eff-dps-summary}
% \end{figure}

\subsection{Triple Parton Scattering (TPS) Processes}

As a natural extension of DPS, triple parton scattering (TPS) offers a deeper probe into parton-parton correlations but presents a formidable experimental challenge due to its much smaller cross-section. Theoretical interest in TPS has grown significantly, with work by d'Enterria and Snigirev predicting a relationship between the effective cross-sections for DPS and TPS, namely $\effXsecTPS \approx 0.82 \times \effXsecDPS$, based on general assumptions about the proton's transverse profile \cite{denterriaTriplePartonScatterings2017}. A crucial breakthrough came from a theoretical study by Shao and Zhang, who proposed that the hadroproduction of three prompt $J/\psi$ mesons is a "golden channel" for observing TPS \cite{shaoTriplePrompt$J2019}. The rationale is that the corresponding SPS contribution to this final state is highly suppressed, making the relative contribution from MPS, and particularly TPS, much larger and more accessible experimentally.

This theoretical proposal was spectacularly confirmed by the CMS experiment, which reported the first observation of triple-$J/\psi$ production in $pp$ collisions at $\sqrt{s} = 13~\mathrm{TeV}$ \cite{thecmscollaborationObservationTripleMeson2023}. This landmark measurement, with a statistical significance exceeding five standard deviations, demonstrated the feasibility of probing TPS at the LHC. The analysis extracted a value of $\effXsecDPS = 2.7^{+1.4}_{-1.0}(\text{exp})^{+1.5}_{-1.0}(\text{theo}) ~\text{mb}$, which is remarkably consistent with previous results from di-quarkonium DPS studies. This result not only validates the theoretical framework but also opens a new frontier in the study of MPS.

Following these pioneering studies, we are motivated to extend the search for TPS to other multi-heavy-flavor final states. We propose to search for the simultaneous production of double $J/\psi$ and $\Upsilon$ mesons, double $J/\psi$ and $\phi$ mesons, and $J/\psi$, $\Upsilon$, and $\phi$ mesons in $pp$ collisions at $\sqrt{s} = 13.6~\mathrm{TeV}$. These channels, involving multiple quarkonia, are expected to have relatively large MPS contributions. It is worth noting that the $pp\to J/\psi+J/\psi+\Upsilon+X$ process is of particular interest. Despite a potentially lower yield, its six-muon final state allows for a very clean reconstruction, leveraging the excellent muon identification and measurement capabilities of the CMS detector.

\subsection{The Large Hadron Collider (LHC)}

The Large Hadron Collider (LHC) operated by the European Organization of Nuclear Research (CERN) is the most powerful accelerator on earth today.
The LHC collides beams of protons with an energy of up to 6.8 TeV, corresponding to a center-of-mass energies of up to $\sqrt{s}=13.6~\mathrm{TeV}$.
Located approximately 100 meters underground across the Swiss-Franco border near Geneva, the LHC features a main storage ring with a circumference of approximately 27 kilometers, capable of accelerating more than 2800 proton bunches simultaneously, each bunch containing approximately $10^11$ protons.
Protons accelerated in the LHC traverse through the storage ring in opposite directions and intersect at four interaction points to collide at a time interval of 25 nanoseconds and deliver an instantaneous luminosity up to $2.5\times 10^{34} ~\text{cm}^{-2}\cdot\text{s}^{-1}$\cite{CMS:LUMI-PUB}.

Four major particle detectors, CMS, ATLAS, ALICE and LHCb, are each located at one of the four interaction points, measuring the key properties of particles produced in collision with their unique detector modules, and acquire data for further physics analysis.

% The figure below was in your original document. I have commented it out as I cannot generate the image file.
% \begin{figure}[!htbp]
%     \centering
%     \includegraphics[width=1.0\linewidth]{images/CMS_pileup_allYears_run3.png}
%     \caption{Average number of interactions per bunch crossing in LHC Run 3 by year\cite{CMS:LUMI-PUB}}
%     \label{fig:CMS_pileup}
% \end{figure}

One important consequence of the high luminosity is the "pileup" effect, i.e., in each bunch crossing more than one hard scattering event happens.
In LHC Run 3, the average number of interactions in each bunch crossing reaches 60, as shown by Figure \ref{fig:CMS_pileup}.
\cite{CMS:LUMI-PUB} Such effect may introduce a higher combinatorial background in the analysis and require advanced analysis techniques to mitigate its effect.

\subsection{The CMS Detector}

The Compact Muon Solenoid (CMS) (shown in Figure \ref{fig:CMS-disection}) is one of the two general-purpose detectors on LHC.
The detector itself measures 21 meters long and 15 meters in diameter, with a total weight of approximately 14,000 tonnes.

% The figure below was in your original document. I have commented it out as I cannot generate the image file.
% \begin{figure}[!htbp]
%     \centering
%     \includegraphics[width=1.0\linewidth]{images/CMS_disection_Run2.png}
%     \caption{A schematic dissection of the CMS detector\cite{CMS_CUTAWAY_DIAGRAM}}
%     \label{fig:CMS-disection}
% \end{figure}

A defining characteristic of CMS is its powerful superconducting solenoid magnet with a inner bore of 5.9 meters and a length of 12.9 meters, capable of producing a magnetic field of 3.8 T inside its bore with a direction along the beam line, where the inner tracker and calorimeter modules are accommodated.
The strong-magnetic-field design is in line with the demand for good momentum resolution within a relatively compact spectrometer.\cite{CMS_JINST_2008}

Another distinctive advantage of CMS is its muon measurement capability, owing to its muon sub-detector module designs.
With the return field of the superconducting solenoid strong enough to saturate 1.5 m of iron, the 4 muon "stations" are integrated inside the iron return yoke of the solenoid, providing a bending field of around 2 T and ensuring both robustness and full geometrical coverage.
Each muon "station" consists of several layers of aluminium drift tubes (DT) in the barrel region and and cathode strip chambers (CSCs) in the endcap region, complemented by resistive plate chambers (RPCs).
These detector modules work in tandem with the inner silicon tracker modules to produce a total reconstruction and identificaton efficiency of $> ~ 96\%$ and relative momentum resolution of $2\%$ for most muons and $10\%$ even for TeV muons.\cite{CMS_MUON_PERF_13TEV}

\section{Datasets and Event Selection}

\subsection{The CMS Trigger System and Criteria}

LHC collisions occur at a rate of 40 MHz, which corresponds to a data production rate of around 40 TB/s, making it impossible to store all events.
The CMS experiment therfore employs a a two-tiered trigger system to preserve only events of physical importance.
A hardware-based Level 1 Trigger (L1T), run on FPGAs and ASICs, reduces the event rate to 100 kHz.
A software-based High Level Trigger (HLT), run on computer farms further reduces the average output rate to around 1.5 kHz.

The CMS datasets typically accept events passing any one of a certain set of trigger conditions.
In our analysis, we require the events to be triggered by the \textsc{HLT\_Dimuon0\_Jpsi3p5\_Muon2\_v} or the \textsc{HLT\_Trimuon5\_3p5\_2\_Upsilon\_Muon\_v}, with the primary criteria of each trigger listed in Table \ref{tab:trigger}.
The former trigger is used to extract potential $J/\psi\to\mu^+\mu^-$ processes and the latter one is used to obtain more $\Upsilon(nS)$-containing samples.

\begin{table*}[ht]
    \centering
    \caption{Primary selection criteria of the triggers employed}
    \begin{tabular}{p{0.45\textwidth}p{0.45\textwidth}}
    \toprule
    \textbf{HLT\_Dimuon0\_Jpsi3p5\_Muon2\_v}  &
    \textbf{HLT\_Trimuon5\_3p5\_2\_Upsilon\_Muon\_v} \\
    \midrule
    At least 3 muons present and satisfying: &
    At least 3 muons present and satisfying: \\
    \begin{itemize}[topsep=0pt, leftmargin=*]
        \item Transverse momentum $p_T > 2.0\GeVc$
        \item Pseudorapidity $|\eta| < 2.5$
    \end{itemize} &
    \begin{itemize}[topsep=0pt, leftmargin=*]
        \item Transverse momentum $p_T > 2.0\GeVc$
        \item Pseudorapidity $|\eta| < 2.5$
    \end{itemize}\\
    & $\mathbf{\cdot}$ At least 1 muon satisfying $p_T > 5.0 \GeVc$ \\
    \midrule
    With at least one pair of muon satisfying : &
    With at least one pair of muon satisfying : \\
    \begin{itemize}[topsep=0pt, leftmargin=*]
        \item $p_T > 3.5\GeVc$
        \item Invariant mass $m_{\mu\mu}$ satisfying $2.95\GeVcs < m_{\mu\mu} < 3.25 \GeVcs$
        \item Tracks fitted to a common vertex with probability > $0.5\%$
    \end{itemize} &
    \begin{itemize}[topsep=0pt, leftmargin=*]
        \item $p_T > 3.5\GeVc$
        \item Invariant mass $m_{\mu\mu}$ satisfying $8.5\GeVcs < m_{\mu\mu} < 11.4 \GeVcs$
        \item Tracks fitted to a common vertex with probability > $0.5\%$
    \end{itemize} \\
    \bottomrule
    \end{tabular}

    \label{tab:trigger}
\end{table*}

\section{Conclusions}

\subsection{Collision Data Analysis Result Summary}


\subsection{Further Work and Future Prospects}

In the upcoming months, an event generation framework for $pp\to J/\psi+J/\psi+\phi+X$ and $pp\to J/\psi+\Upsilon+\phi+X$ processes will be developed.
More samples will be generated to improve the statistics of the analysis.
A filter configuration will be introduced at generation-level to improve the overall efficiency of event generation and simulation.

With Monte Carlo samples, efficiency and systematic errors will be evaluated for the searched processes and can be used to determine the actual cross-section of the processes, employing event-by-event correction.
Separation of the SPS, DPS and TPS components will also be studied in detail, with the aim of obtaining a more accurate estimation of the cross-section of the TPS component.

Most of the results above have been presented at the CMS B-physics Group Production and Properties Meeting on 9th July, 2025 by the author.
Positive response has been received from the group members and the author would like to communicate with the primary author of the triple-$J/\psi$ study for further collaboration and discussion.

\section{Acknowledgements}

This work is carried out under the supervision of Dr.
Zhen Hu and in collaboration with Xing Cheng from Zhili College and Zhenpeng Shi from Department of Physics.

Much help has been received from the Tsinghua CMS group, including but not limited to the following members: Dr.
Zhen Hu, Yiyang Zhao, Xining Wang, Shiyang Chen.
The author would like to express his gratitude for their help and support.

\bibliographystyle{unsrt}
\bibliography{mainTemplatePDF.bib}
\end{document}

```

# latex-template-arxiv-preprint
A simple LaTeX template for Technical Reports, arXiv preprints &amp; 2-column Conference papers

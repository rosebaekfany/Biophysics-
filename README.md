# Biophysics
Biophysics course final project

## Cancer Stem Cells and Tumor Population Dynamics

This project explores the role of **Cancer Stem Cells (CSCs)** in driving tumor growth and heterogeneity. By combining **biological insights** with **mathematical population dynamics models**, the study investigates how CSCs contribute to cancer progression, their experimental identification, and challenges associated with targeting them.

---

1. **Introduction to Cancer Stem Cells (CSCs)**

   * CSCs are a small subpopulation within tumors.
   * They exhibit **self-renewal** and **differentiation**, fueling cancer growth.
   * First identified by John Dick in AML during the late 1990s.

2. **Experimental Identification of CSCs**

   * Typically involves **cell sorting (FACS)** using surface markers (e.g., CD44+/CD24−).
   * Tumor formation is validated via transplantation into immunocompromised mice.
   * Challenges: lack of universal markers, reversible marker expression, and loss of tumor microenvironment context.

3. **Population Dynamics Modeling**

   * **Branching process models** describe CSC division: symmetric renewal, asymmetric division, or differentiation.
   * Key parameter: **ϵ = p₂ − p₀** (net CSC increase per generation).
   * Dynamics equations predict tumor growth is largely driven by CSC expansion.
   * Phenotypic switching models highlight the resilience of CSC populations under depletion, often showing overshoot behavior mediated by **miRNA networks**.

4. **Biological Predictions**

   * Normal tissue (ϵ = 0): higher senescence, fewer CSCs.
   * Tumors (ϵ > 0): reduced senescence, more CSCs.
   * Aggressive tumors show higher CSC fractions.
   * Predictions validated with melanoma growth studies (e.g., ABCG2+ vs. ABCG2− cells).

## 📚 References

1. La Porta, C. A. M., & Zapperi, S. (2012). *Physics of Cancer*.
2. Michor, F., et al. (2005). *Mathematical models of cancer stem cells*.
3. Gupta, P. B., et al. (2011). *Stochastic state transitions in cancer populations*.
4. Roesch, A., et al. (2010). *Phenotypic switching in melanoma*.
5. Sellerio, P., et al. (2015). *miRNA-driven phenotypic switching in melanoma*.

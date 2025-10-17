## Financial Distress Risk and Intangible Asset Portfolio

**University of Warwick – MSc Economics and International Financial Economics Dissertation (2025)**

**Author:** Lei Sze Wing Sharon

### Overview

This research investigates how **intangible asset portfolios** influence firms’ **financial distress risk** and **capital structure**, focusing on whether industry-standardization of intangibles reduces exposure to firm-specific risk. The study extends the **Maksimovic & Zechner (1991)** industry equilibrium framework to the intangible economy, where innovation, R&D, and intellectual capital increasingly determine firm value and financing capacity.

### Research Objectives

* Examine the relationship between **intangible asset alignment** and **cash flow volatility**.
* Evaluate how **intangible standardization** affects firms’ ability to sustain leverage in competitive versus concentrated industries.
* Quantify the role of **collateral capacity** in mediating financial stability for intangible-intensive firms.

### Methodology

The empirical analysis uses **panel data of 4,600+ North American firms (2000–2024)** from **Compustat (WRDS)**.
Data preparation and estimation were implemented using **Stata 18**, integrating advanced econometric and data-cleaning techniques:

* **Data Cleaning & Transformation:**
* 
  * Harmonization of panel identifiers and industry codes (SIC2, SIC3).
  * Multi-stage imputation strategy: within-firm interpolation, industry–year medians, and firm-level means.
  * Winsorization of key accounting ratios to mitigate outlier influence.

* **Variable Construction:**

  * Core financial ratios: profitability, leverage, tangibility, Tobin’s Q.
  * **Intangible Portfolio Index (IP):** principal component (PCA) of R&D intensity, identifiable intangibles, and total intangibles.
  * **Cash-Flow Volatility (CFV):** rolling standard deviation of operating cash flow to assets over 3–5 years.
  * **Natural Hedge (NH):** proximity to industry-median intangible profile, scaled by within-industry dispersion.
  * **Industry Concentration:** HHI-based classification into *competitive* and *concentrated* sectors.

* **Econometric Models:**

  * Benchmark **OLS panel regressions**.
  * **Dynamic panel GMM** system estimation to address endogeneity and persistence in leverage and risk.

### Key Findings

* Firms closer to the industry’s technological core **do not consistently exhibit lower cash-flow volatility**, suggesting a limited natural hedge effect in intangible-driven sectors.
* The **leverage–risk relationship** remains positive and stronger for intangible-intensive firms, consistent with **risk-shifting incentives**.
* Tangible and identifiable intangibles modestly improve financial stability, while non-standardized intangibles increase volatility and financing constraints.

### Contribution

This project contributes to **corporate finance and industrial organization** literature by:

* Extending classical equilibrium models to account for **intangible-driven uncertainty**.
* Providing a **replicable Stata-based workflow** for constructing firm-level intangible alignment measures.
* Offering insights into how **asset standardization and collateralizability** shape financial resilience in the modern economy.

### Skills & Tools

* **Software:** Stata, LaTeX, WRDS/Compustat
* **Techniques:** Panel Data Analysis, System GMM, PCA, Winsorization, Multi-source Data Integration
* **Focus Areas:** Financial Risk Analysis, Corporate Capital Structure, Intangible Asset Valuation, Empirical Research


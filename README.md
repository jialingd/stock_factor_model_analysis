Exploring One- and Two-Factor Models for U.S. Stock Returns 

This project analyzes daily returns for 28–30 major U.S. corporations (2015) to understand market-wide and sector-specific risk factors using statistical factor models.
Through exploratory data visualization, kernel density estimation, and factor analysis, the study decomposes stock co-movements into latent components that capture shared market dynamics.




Objectives:

Compare raw closing prices vs. log-returns for scale-invariant comparability.

Use kernel density estimation (KDE) to assess non-Gaussian behavior of log-returns.

Fit a one-factor model to extract a common market risk factor.

Extend to a two-factor model to capture additional sectoral variation.

Evaluate factor loadings, factor scores, and covariance structure through bootstrap confidence intervals.




Analysis Outline

1. Data Preparation – Compute daily log-returns for 28 large U.S. stocks across 2015.

2. Distributional Analysis – Compare Gaussian and KDE fits for individual assets (e.g., Boeing).

3. One-Factor Model – Extract market factor using principal-component-based estimation.

4. Interpret sector-level loadings (financials and industrials show highest exposure).

5. Validate covariance consistency using theoretical and bootstrap tests.

6. Bootstrap Confidence Intervals – Quantify uncertainty in factor loadings (85% and 95% CIs).

7. Two-Factor Model Extension –Identify second factor representing industry-specific behavior (e.g., energy or tech).

Assess impact of adding assets like Visa and Nike on model structure and volatility.



📊 Key Findings

Log-returns are more comparable than raw prices across assets.

Gaussian assumptions underestimate peak and tail densities; KDE fits are superior.

One-factor model captures a broad market component explaining most variation.

Bootstrap CI results confirm model consistency (ratio ≈ 1 within 95% CI).

Two-factor model introduces meaningful sector-specific differentiation.

# Multiple Linear Regression (MLR) Marketing Optimization Model

An end-to-end econometric and data science workflow evaluating the return on investment (ROI) across various advertising channels (`TV`, `Radio`, and `Social Media`) to predict total `Sales`.

## 📈 Model Output & Statistical Evaluation
* **Adjusted R-squared — ~0.902**: Explains **90.2%** of the underlying variance in company `Sales` using the combined marketing spend matrix.
* **F-statistic Significance ($p < 0.001$)**: Confirms the multi-channel framework provides predictive capabilities superior to a naive sample mean baseline.

## 📋 Operational Model Equation
$$	ext{Sales} = 265.48 + 5.17(	ext{Radio}) - 0.08(	ext{Social Media}) - 208.38(	ext{TV\_Low}) - 104.79(	ext{TV\_Medium})$$

## 🎯 Strategic Business Insights
1. **Prioritize TV Spend Tiers**: Shifting from High to Low TV strips away an average of **208.38 sales units**. Premium TV must remain the core anchor.
2. **Leverage Radio to Scale**: Every unit scaled in traditional Radio Spend yields a predictable return of **5.17 units** ($p < 0.001$).
3. **Freeze Standalone Social Spend**: Social Media returns an insignificant p-value ($0.709$). Redirect these funds to Radio or TV.

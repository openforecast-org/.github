<p align="center">
  <img src="assets/of-logo-full.png" alt="OpenForecast" width="440">
</p>

<p align="center"><em>Actionable insights, from research-grade forecasting.</em></p>

---

**OpenForecast** builds open-source forecasting tools and provides consulting and training in demand forecasting and inventory management. Our packages are the rigorous engine behind that work — grounded in peer-reviewed research, refined over a decade, and used by analysts worldwide.

## Packages

### smooth — forecasting that plans around uncertainty

State-space time series forecasting for **R and Python**, built on the **ADAM** framework that unifies exponential smoothing (ETS), ARIMA, and regression in a single model. It produces full probabilistic forecasts rather than single point predictions, handles multiple seasonalities and short histories, and — crucially for supply chain — models the **intermittent demand** that standard tools get badly wrong.

```r
# R
install.packages("smooth")
```

```bash
# Python
pip install smooth
```

[GitHub](https://github.com/config-i1/smooth) · [CRAN](https://cran.r-project.org/package=smooth) · [PyPI](https://pypi.org/project/smooth/)

### greybox — the model-building and evaluation toolkit

Companion tools for **R** that bring the real drivers of demand into the model: regression with information-criteria-based variable selection, explanatory forecasting, and honest forecast evaluation. This is how you explain *why* demand moves — promotions, pricing, seasonality — instead of extrapolating from history alone.

```r
# R
install.packages("greybox")
```

```bash
# Python
pip install greybox
```

[GitHub](https://github.com/config-i1/greybox) · [CRAN](https://cran.r-project.org/package=greybox) · [PyPI](https://pypi.org/project/greybox/)

## What these solve

- **Forecasts you can plan around** — honest uncertainty around every forecast, so safety stock can be set deliberately instead of guessed.
- **The hard cases, handled** — intermittent and slow-moving items, spare parts, and short data histories where bigger models fail.
- **Demand explained, not just extrapolated** — bring promotions, pricing, and seasonality into the model as real drivers.
- **Glass-box, not black-box** — transparent, interpretable models you can explain to finance and stand behind.
- **Built to scale** — automated model selection across thousands of series, in minutes.

## Consulting & training

The packages are freely available, and that transparency is the point. Our value is in applying them: turning your demand data and ERP into working forecasting and replenishment decisions — correcting for stockout-censored sales, capturing your demand drivers, and building models around how your business actually runs. We also run practitioner training in forecasting, inventory management, and analytics.

**Website:** [openforecast.org](https://openforecast.org) · **Email:** mail@openforecast.org · **LinkedIn:** [OpenForecast](https://www.linkedin.com/company/openforecast)

---

<sub>Methodology: ADAM (Svetunkov, 2023). Built and maintained by the OpenForecast team.</sub>

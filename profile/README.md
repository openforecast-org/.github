<p align="center">
  <img src="../assets/of-logo-full.png" alt="OpenForecast" width="440">
</p>

<p align="center"><em>Actionable insights, from research-grade forecasting.</em></p>

---

**OpenForecast** builds open-source forecasting tools and provides consulting and training in demand forecasting and inventory management. Our packages are the rigorous engine behind that work: grounded in peer-reviewed research, refined over a decade, and used by analysts worldwide.

## The packages

### smooth — state-space forecasting for R and Python

The core of the toolkit: forecasting built on the **ADAM** framework, which unifies exponential smoothing (ETS), ARIMA, and regression in a single state-space model. It produces full probabilistic forecasts rather than single point predictions, handles multiple seasonalities and short histories, and models the **intermittent demand** that standard tools get badly wrong.

```r
# R
install.packages("smooth")
```

```bash
# Python
pip install smooth
```

[Repository](https://github.com/openforecast-org/smooth) · [CRAN](https://cran.r-project.org/package=smooth) · [PyPI](https://pypi.org/project/smooth/)

### greybox — model building and evaluation for R and Python

The companion toolkit that brings the real drivers of demand into the model: regression with information-criteria-based variable selection, explanatory forecasting, and honest forecast evaluation. This is how you explain *why* demand moves (promotions, pricing, seasonality) instead of extrapolating from history alone. The pacakge also includes tools for demand classification tehniques.

```r
# R
install.packages("greybox")
```

```bash
# Python
pip install greybox
```

[Repository](https://github.com/openforecast-org/greybox) · [CRAN](https://cran.r-project.org/package=greybox) · [PyPI](https://pypi.org/project/greybox/)

### legion — multivariate forecasting for R

Models for forecasting several related series together via the vector exponential smoothing. Useful when products, regions, or channels move together and when shared dynamics carry information a univariate model throws away.

```r
install.packages("legion")
```

[Repository](https://github.com/openforecast-org/legion) · [CRAN](https://cran.r-project.org/package=legion)

### muse — Multiple Unobserved Sources of Error (C++)

Research-grade implementation of the **MSOE** state-space framework — the multiple-source-of-error counterpart to the single-source models. Where the frontier of our methodology work lives.

[Repository](https://github.com/openforecast-org/muse)

### fcompdata — forecasting competition datasets for Python

The M1, M3, and tourism competition datasets, packaged for Python — for benchmarking your methods against the same data the field uses.

[Repository](https://github.com/openforecast-org/fcompdata)

## What these solve

- **Forecasts you can plan around** — honest uncertainty around every forecast, so safety stock can be set deliberately instead of guessed.
- **The hard cases, handled** — intermittent and slow-moving items, spare parts, and short data histories where bigger models fail.
- **Demand explained, not just extrapolated** — bring promotions, pricing, and seasonality into the model as real drivers.
- **Glass-box, not black-box** — transparent, interpretable models you can explain to finance and stand behind.
- **Built to scale** — automated model selection across thousands of series, in minutes.

## Consulting & training

The packages are freely available, and that transparency is the point. Our value is in applying them: turning your demand data and ERP into working forecasting and replenishment decisions: correcting for stockout-censored sales, capturing your demand drivers, and building models around how your business actually runs. We also run practitioner training in forecasting, inventory management, and analytics.

**Website:** [openforecast.org](https://openforecast.org) · **Email:** mail@openforecast.org · **LinkedIn:** [OpenForecast](https://www.linkedin.com/company/openforecast)

---

<sub>Methodology: [ADAM (Svetunkov, 2023)](openforecast.org/adam). Built and maintained by the OpenForecast team.</sub>

# Education and Internet Use

An interactive Quarto website exploring education index and internet use by
country over time.

## View the website

The published site is available at:

<https://brookehiggins.github.io/education-internet-trends/>

## Render locally

Install [Quarto](https://quarto.org/) and the R packages used by the report:

```r
install.packages(c("tidyverse", "sf", "plotly"))
```

Then render the site from this directory:

```sh
quarto render
```

The rendered website is written to `_site/`.

## Data sources

- Education index and internet use: [Gapminder](https://www.gapminder.org/data/)
- Country boundaries: [DataHub country GeoJSON](https://datahub.io/core/geo-countries)

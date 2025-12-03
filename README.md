# MGWRSAR: Extended Documentation & Vignettes

This repository hosts the **extended, interactive, and full-resolution vignettes** for the R package **[mgwrsar](https://cran.r-project.org/web/packages/mgwrsar/index.html)**    .

## 🎯 Why this repository?

To comply with **CRAN package size limitations** and to provide high-quality interactive maps (Leaflet, Plotly), the full HTML vignettes are hosted here via **GitHub Pages**. 

The vignettes included inside the installed package are "stub" versions that redirect to the links below.

## 📚 Available Vignettes

Click on a topic below to view the full interactive documentation in your browser.

| Topic | Description | Link |
| :--- | :--- | :---: |
| **General Usage** | A complete guide to the main functions, syntax, and workflow of `mgwrsar` using French House Price Data. | [**View Vignette**](https://ggeniaux.github.io/mgwrsar_vignettes/Intro_french_data.html) |
| **Spatial Autocorrelation** | GWR and Mixed GWR with spatial autocorrelation. | [**View Vignette**](https://ggeniaux.github.io/mgwrsar_vignettes/GWR-and-Mixed-GWR-with-spatial-autocorrelation.html) |
| **Speeding up GWR** | Speeding up GWR like models with mgwrsar package using Target Points, rough gaussian kernel and parallelisation. | [**View Vignette**](https://ggeniaux.github.io/mgwrsar_vignettes/Speeding_up_GWR_like_models.html) |
| **Space-Time GWR** | GWR and MGWR with Space-Time Kernels. | [**View Vignette**](https://ggeniaux.github.io/mgwrsar_vignettes/GWR-with-Space-Time-Kernels.html) |
| **Multiscale GWR** |Multiscale GWR using top down scale approaches. | [**View Vignette**](https://ggeniaux.github.io/mgwrsar_vignettes/Multiscale-GWR-using-top-down-scale-approach.html) |

> *Note: If a link returns a 404 error, please check that the corresponding HTML file is present in this repository.*

## 📦 Installing the Package

You can install the latest stable version of `mgwrsar` from CRAN:

```r
# From CRAN
install.packages("mgwrsar")

# Digital Archives and Methods

**Author:** Julie Oestgaard Dahl (AU773313)
**Course:** Digital Archives and Methods, Summer University 2026
**Institution:** Aarhus University
**Instructor:** Jonathan Lanz
**ECTS:** 10
**Contact:** [202405725@post.au.dk](mailto:202405725@post.au.dk)

## About this repository

This repository contains my exam submission for Digital Archives and Methods. The course explores how digital tools and computational methods can be used to work with, analyze, and present archival and historical data. All work was done in R and RStudio, using R Markdown documents knitted to HTML.

## Repository structure

```
├── Monarchs/
│   └── ...
├── Final_Project/
│   └── ...
└── README.md
```

* `Monarchs/` — Part 1 of the exam: an assignment working with a dataset of monarchs.
* `Final_Project/` — Part 2 of the exam: the final project.

## Final Project

**Title:** The Coil Campaign in Greenland

This project examines how and to what extent the Danish government's Coil Campaign (*Spiralkampagnen*), part of the modernization process in Greenland, affected the country's population growth and development before, during, and after the campaign. Using population data from Greenland spanning 1840–2025, the project applies data visualization in R (line plots and interactive annual growth-rate plots) to trace population trends around the campaign's peak in the late 1960s and 1970s.

### Data

The data comes from two sources: the World Bank (total population of Greenland, 1961–2025) and Danmarks Statistik (a PDF document, "Folketællingen i Grønland den 31. december 1945", covering earlier population counts). The data was cleaned and combined into a single csv file. Population counts before 1961 are sporadic rather than annual, and there is a data gap between 1946–1960 where no data was available from either source; both limitations are flagged in the visualizations.

### Key findings

* Greenland's population grew almost exponentially from 1840 until the late 1960s.
* Annual population growth declined sharply from 1970 onwards, reaching its lowest point of roughly -0.6% in 1977 — coinciding with the period in which at least 4,500 IUDs were inserted in Greenlandic women and girls between 1966 and 1970, often without proper consent.
* Population growth has remained low since, rarely exceeding 1.0% after 1989, and was roughly -0.009% in 2025.

## How to run this project

1. Clone the repository:

```
git clone https://github.com/Digital-Methods-HASS/AU773313_dahl_julie.git
```

2. Open the relevant `.Rmd` file in RStudio.
3. Install required packages, e.g.:

```
install.packages(c("tidyverse", "tidytext"))
```

4. Knit the R Markdown file to HTML to reproduce the analysis and output.

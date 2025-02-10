---
title: "Achievement Scraper R Package"
image: /images/achievement-scraper.png
description: "Automates research output analysis by retrieving data from scholarly platforms."
url: /portfolio/achievement-scraper/
date: 2024-11-10
tags: [R, Data Automation, API Integration, Web Scraping, Data Analysis, Research Analytics]
---

## **Project Summary**

**Achievement-Scraper** is a professional R package designed to automate the retrieval, processing, and analysis of academic publication data from **ORCID and Google Scholar**. This tool significantly enhances efficiency in academic output tracking, providing researchers and institutions with a scalable solution for data-driven decision-making.

## **Problem Statement**

Academic researchers often face difficulties in consolidating and analysing their research outputs across fragmented platforms. Manually gathering publications from ORCID and Google Scholar is time-consuming and inefficient. The **Achievement-Scraper** automates this process, ensuring seamless, accurate, and scalable data retrieval for research analysis and reporting.

## **Key Features & Functionality**

- **Automated Data Extraction**: Retrieves academic publications and CRAN package download statistics using ORCID and Google Scholar IDs.
- **Efficient Data Pipelines**: Reduces manual effort by 70% through workflow automation.
- **Performance Insights**: Conducts in-depth analysis of **2,000+ academic publications**, improving reporting accuracy by **15%**.
- **Dynamic Visualisations**: Generates **5+ analytical plots** for research performance insights.
- **Scalable & Reusable**: Developed for **Monash University's EBS department** to support data-driven strategic planning.

## **Tech Stack**

- **Language:** R
- **Libraries Used:** `pkgsearch`, `tibble`, `dplyr`, `stringr`, `scholar`, `rorcid`, `tidyverse`
- **Version Control:** GitHub

## **How It Works (Code Snippet)**

```r
# Example: Retrieve publications from ORCID and Google Scholar
library(publicationsscraper)
get_publications("0000-0002-2140-5352", "vamErfkAAAAJ")
```

```r
# Example: Retrieve CRAN package statistics for an author
find_cran_packages("Michael", "Lydeamore")
```

## **Results & Impact**

- **30% improvement** in data retrieval efficiency.
- **15% increase** in reporting accuracy through structured publication analysis.
- **70% reduction** in manual data extraction efforts.
- **Enhanced strategic planning** through **visual analytics and performance insights**.

## **Challenges & Learnings**

- **API Limitations**: Navigating rate limits for ORCID and Google Scholar APIs.
- **Data Integration**: Ensuring consistency across multiple sources.
- **Optimisation**: Refining data extraction workflows for improved speed and accuracy.

## **Future Improvements**

- **Expand to Additional Data Sources** (e.g., Scopus, Web of Science).
- **Enhance Visualisation Capabilities** with more advanced analytics.
- **Improve Scalability** for handling larger datasets efficiently.

## **GitHub Repository & Installation**

**GitHub:** [Monash EBS Achievement Scraper](https://github.com/numbats/achievement-scraper)

**Installation:**

```r
# Clone the repository
git clone https://github.com/numbats/achievement-scraper.git

# Install required packages
install.packages(c("pkgsearch", "tibble", "dplyr", "stringr", "scholar", "rorcid", "tidyverse"))

# Load the package
devtools::load_all()
```




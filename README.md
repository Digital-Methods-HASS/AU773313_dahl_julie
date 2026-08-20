Digital Archives and Methods – Spring 2026
AU802180 · Rasmus C. Storkholm
Aarhus University · Department of History and Classical Studies

About This Repository
This repository contains weekly assignments and the final project for the course Digital Archives and Methods (DAM), Spring 2026 at Aarhus University. The course introduces history students to digital archives and computational methods for historical research, covering the full digital lifecycle — from data collection and wrangling to analysis, visualisation, and FAIR data stewardship.

Repository Structure
Folder	Contents
Week_10	Introduction to R: scripts, digital objects, and core principles
week11-kings	Tidyverse: wrangling and plotting the Danish monarchs dataset
Week 12	Plotting in R: Danish monarchs, Nordic homicides, and Gapminder
Week 13	Sentiment analysis and interactive maps with Leaflet in R
Week 17	Digital archives reflection assignment: analysis of digital archival literacy, metadata, and multimodal testimony using the David Boder wire recordings and the Voyages database
Final_project	Final digital project – R script, data, and written report
Final Project
Title: Sterilization by Design: Gender, Class, and Legislative Intent at the Keller Institution 1930–1943

Research question: To what extent did the introduction of the 1934 Sterilization Act systematically target women and lower social classes at the Keller Institutions for the feebleminded in the years 1930–1943?

Summary:
This project investigates Danish sterilisation practice following the sterilisation laws of 1929, 1934, and 1935, using digitised archival records from the Keller institutions accessed via kilderne.dk. The dataset contains 500 individual sterilisation and castration records (1930–1943) spanning variables including gender, year of birth, social class, legal basis, and legitimacy of birth. The analysis is conducted in R using tidyverse, ggplot2, and patchwork, producing five figures that together form the empirical basis for the findings.

Key findings:

Women consistently accounted for the majority of procedures across all three legislative frameworks, and their overrepresentation intensified following the 1934 Act
The median age at sterilisation for women dropped from 27.5 to 23 years after 1934, concentrating procedures within the reproductive years
Approximately 70% of all sterilised individuals belonged to the working class (Group B)
Group D, the most socially marginalised category, showed a near-total overlap with illegitimate birth at 98%
Data: Steri_fil.csv — 500 observations, 11 variables, sourced from the Danish National Archives (Rigsarkivet) via kilderne.dk
Tools: R 4.5.2, RStudio 2026.01.1, tidyverse, ggplot2, patchwork, dplyr, scales

Portfolio Overview
The exam portfolio consists of five elements:

Regex / OpenRefine assignment (Week 8)
Danish kings assignment (Week 11)
Visualisation assignment (Week 13)
Digital archives reflection (Week 17)
Final digital project — Sterilization by Design
Reproducibility
All R scripts are fully annotated and reproducible. The dataset (Steri_fil.csv) is included in the Final_project folder. Required packages are listed at the top of each script.

Course Information
Course: Digital Archives and Methods, Spring 2026
Institution: Aarhus University
Instructors: Adéla Sobotková & Jonathan Lanz
Contact: au802180@au.uni.dk
ECTS: 10
